<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygvjc2bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygvjc2bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pangolin" {...props}></Icon>
