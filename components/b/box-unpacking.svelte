<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbr-uubfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbr-uubfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:box-unpacking" {...props}></Icon>
