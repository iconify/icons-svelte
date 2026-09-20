<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umpeo9btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umpeo9btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-z-circle-outline" {...props}></Icon>
