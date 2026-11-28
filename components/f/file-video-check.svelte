<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7trzwh8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7trzwh8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-video-check" {...props}></Icon>
