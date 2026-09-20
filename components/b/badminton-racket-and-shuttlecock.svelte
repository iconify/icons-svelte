<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y97_zp_7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y97_zp_7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:badminton-racket-and-shuttlecock" {...props}></Icon>
