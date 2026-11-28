<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ift-esbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ift-esbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-search" {...props}></Icon>
