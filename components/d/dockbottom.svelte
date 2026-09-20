<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_gb2ybwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_gb2ybwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:dockbottom" {...props}></Icon>
