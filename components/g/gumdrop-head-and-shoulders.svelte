<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz7p0yhdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pz7p0yhdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gumdrop-head-and-shoulders" {...props}></Icon>
