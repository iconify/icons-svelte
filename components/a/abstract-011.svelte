<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-xn1obdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-xn1obdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-011" {...props}></Icon>
