<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjk242bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yjk242bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:link" {...props}></Icon>
