<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xccoi3b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xccoi3b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:goods-outline" {...props}></Icon>
