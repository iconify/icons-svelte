<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvuzxfyik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wvuzxfyik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parallelogram-duotone" {...props}></Icon>
