<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wod6j874l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wod6j874l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pause-box" {...props}></Icon>
