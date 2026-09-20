<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i72reac_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i72reac_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hook-off" {...props}></Icon>
