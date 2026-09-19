<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrolc2zcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nrolc2zcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-046" {...props}></Icon>
