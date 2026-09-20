<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcn9d8shr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rcn9d8shr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-in-car" {...props}></Icon>
