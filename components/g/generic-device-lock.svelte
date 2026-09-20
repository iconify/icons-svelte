<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhhznw4hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhhznw4hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-lock" {...props}></Icon>
