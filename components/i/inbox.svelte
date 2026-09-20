<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0crjlb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m0crjlb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:inbox" {...props}></Icon>
