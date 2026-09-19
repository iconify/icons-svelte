<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z47rp0b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z47rp0b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cigar" {...props}></Icon>
