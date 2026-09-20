<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw3nfyb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gw3nfyb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-palm-tree" {...props}></Icon>
