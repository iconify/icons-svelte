<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0lx5-bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0lx5-bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:circle-pause" {...props}></Icon>
