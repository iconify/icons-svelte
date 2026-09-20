<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj6099xta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jj6099xta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fillet-knife" {...props}></Icon>
