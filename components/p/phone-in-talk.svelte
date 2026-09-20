<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh85sebgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh85sebgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-in-talk" {...props}></Icon>
