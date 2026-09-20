<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1hvo3b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p1hvo3b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-arrows-up-down" {...props}></Icon>
