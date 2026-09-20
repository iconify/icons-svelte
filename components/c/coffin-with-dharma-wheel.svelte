<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy7urieex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iy7urieex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-dharma-wheel" {...props}></Icon>
