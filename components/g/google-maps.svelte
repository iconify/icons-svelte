<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymc-z9bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":480};
const content = `<path class="ymc-z9bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:google-maps" {...props}></Icon>
