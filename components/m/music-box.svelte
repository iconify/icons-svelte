<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vszc59cox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vszc59cox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-box" {...props}></Icon>
