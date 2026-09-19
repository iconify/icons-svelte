<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuy1p_-se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xuy1p_-se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-055" {...props}></Icon>
