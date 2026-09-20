<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra5q_ibby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ra5q_ibby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-droplet" {...props}></Icon>
