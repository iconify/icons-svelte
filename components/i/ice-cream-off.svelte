<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_0hr8blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_0hr8blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ice-cream-off" {...props}></Icon>
