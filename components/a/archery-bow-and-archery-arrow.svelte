<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx_mgsb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lx_mgsb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:archery-bow-and-archery-arrow" {...props}></Icon>
