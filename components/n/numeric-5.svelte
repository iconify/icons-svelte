<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvwwtebuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvwwtebuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-5" {...props}></Icon>
