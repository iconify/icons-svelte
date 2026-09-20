<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkese0awh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lkese0awh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-canoe" {...props}></Icon>
