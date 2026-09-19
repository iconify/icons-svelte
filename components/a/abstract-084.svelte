<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz37dabew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yz37dabew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-084" {...props}></Icon>
