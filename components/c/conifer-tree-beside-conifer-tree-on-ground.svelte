<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir2pffbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ir2pffbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-beside-conifer-tree-on-ground" {...props}></Icon>
