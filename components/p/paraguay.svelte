<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt2tfpm2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rt2tfpm2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paraguay" {...props}></Icon>
