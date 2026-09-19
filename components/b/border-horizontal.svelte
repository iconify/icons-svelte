<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7udynlxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j7udynlxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:border-horizontal" {...props}></Icon>
