<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbs6kdlzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbs6kdlzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airplane-line" {...props}></Icon>
