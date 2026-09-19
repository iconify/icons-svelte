<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3gvzabwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x3gvzabwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gas-mask" {...props}></Icon>
