<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ydl-l0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ydl-l0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-home-alt" {...props}></Icon>
