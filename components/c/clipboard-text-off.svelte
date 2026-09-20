<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vppzcybrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vppzcybrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-off" {...props}></Icon>
