<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjtn95y0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjtn95y0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-3-bold" {...props}></Icon>
