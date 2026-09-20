<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmb9oon6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmb9oon6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mail-unread" {...props}></Icon>
