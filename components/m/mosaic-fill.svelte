<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvu3bccsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvu3bccsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mosaic-fill" {...props}></Icon>
