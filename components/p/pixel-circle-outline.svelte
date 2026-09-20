<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgly6dx1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wgly6dx1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-circle-outline" {...props}></Icon>
