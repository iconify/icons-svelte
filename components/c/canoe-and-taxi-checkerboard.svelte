<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx2q25b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dx2q25b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-and-taxi-checkerboard" {...props}></Icon>
