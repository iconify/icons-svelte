<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le202y2fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="le202y2fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-with-antenna-array" {...props}></Icon>
