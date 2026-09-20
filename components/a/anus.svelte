<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvqgce3px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bvqgce3px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:anus" {...props}></Icon>
