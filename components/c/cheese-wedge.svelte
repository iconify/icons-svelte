<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8zkq8rtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n8zkq8rtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cheese-wedge" {...props}></Icon>
