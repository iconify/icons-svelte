<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f89pw3byy.css';
import '../../css/d/d2jw_nbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f89pw3byy"/><path class="d2jw_nbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-microphone-alt" {...props}></Icon>
