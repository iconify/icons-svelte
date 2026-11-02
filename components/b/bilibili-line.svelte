<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyysp6bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyysp6bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bilibili-line" {...props}></Icon>
