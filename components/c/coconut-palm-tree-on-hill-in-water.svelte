<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq89bn_un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qq89bn_un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coconut-palm-tree-on-hill-in-water" {...props}></Icon>
