<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh9ckbcjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sh9ckbcjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:church" {...props}></Icon>
