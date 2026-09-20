<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibwid0w7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibwid0w7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-thick-right-bottom-corner-3-bold" {...props}></Icon>
