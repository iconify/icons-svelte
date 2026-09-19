<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq4h58boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gq4h58boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-earrings" {...props}></Icon>
