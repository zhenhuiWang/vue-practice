<template lang="html">
    <div ref='container'>
        <h2>我是子组件的标题</h2>
        <slot>
            只有在没有要分发的内容时才会显示。
        </slot>
    </div>
</template>

<script>
export default {

};
</script>

<style lang="scss">
</style>
