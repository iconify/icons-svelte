<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh_3qzbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zh_3qzbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:ff" {...props}></Icon>
