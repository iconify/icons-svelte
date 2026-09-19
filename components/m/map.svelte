<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1x6j7b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p1x6j7b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:map" {...props}></Icon>
