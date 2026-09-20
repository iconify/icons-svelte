<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnob0x5zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnob0x5zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fit-to-screen" {...props}></Icon>
