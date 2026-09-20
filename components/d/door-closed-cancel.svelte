<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6_32xbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6_32xbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:door-closed-cancel" {...props}></Icon>
