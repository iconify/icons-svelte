<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcyz6xbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rcyz6xbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-beside-oval-broadleaved-tree-on-ground" {...props}></Icon>
