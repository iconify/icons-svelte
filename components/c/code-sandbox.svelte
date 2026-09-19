<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu5g34bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yu5g34bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:code-sandbox" {...props}></Icon>
