<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0srfx45m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y0srfx45m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:airport-terminal-with-plane-ascending" {...props}></Icon>
