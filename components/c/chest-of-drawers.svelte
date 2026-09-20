<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmunubcay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xmunubcay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:chest-of-drawers" {...props}></Icon>
