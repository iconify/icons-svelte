<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mst7sz6bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mst7sz6bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:burger-and-drink-cup-with-straw" {...props}></Icon>
