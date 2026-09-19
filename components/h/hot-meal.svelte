<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9tu38bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t9tu38bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hot-meal" {...props}></Icon>
