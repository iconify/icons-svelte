<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu7afbcqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu7afbcqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dining-room" {...props}></Icon>
