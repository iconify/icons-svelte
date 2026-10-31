<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry0e54byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry0e54byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-download-corner-fill-round" {...props}></Icon>
