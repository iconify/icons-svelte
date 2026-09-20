<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyx02_bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yyx02_bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-down-circle-outline" {...props}></Icon>
