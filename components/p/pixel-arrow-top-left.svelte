<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucluwrb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ucluwrb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-arrow-top-left" {...props}></Icon>
