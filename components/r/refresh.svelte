<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co913ybrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="co913ybrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:refresh" {...props}></Icon>
