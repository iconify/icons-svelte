<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5m4l_bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5m4l_bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:branding-watermark" {...props}></Icon>
