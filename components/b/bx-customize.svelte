<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuf3gdcam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuf3gdcam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-customize" {...props}></Icon>
