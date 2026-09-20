<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gptt6rb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gptt6rb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-erase" {...props}></Icon>
