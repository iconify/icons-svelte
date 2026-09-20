<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft-4nj7qx.css';
import '../../css/c/cl68f3slr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ft-4nj7qx"/><path class="cl68f3slr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:light-blue-heart" {...props}></Icon>
