<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7qzu4b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e7qzu4b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fishbone" {...props}></Icon>
