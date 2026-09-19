<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig5k0rbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5k0rbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-skull" {...props}></Icon>
