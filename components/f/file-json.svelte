<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq4y0sbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq4y0sbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-json" {...props}></Icon>
