<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmgufuxsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmgufuxsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-111" {...props}></Icon>
