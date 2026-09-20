<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz0n5g1vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz0n5g1vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ice-pop" {...props}></Icon>
