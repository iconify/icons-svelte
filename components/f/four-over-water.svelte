<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz6h1pstq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pz6h1pstq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:four-over-water" {...props}></Icon>
