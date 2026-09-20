<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9cnqzbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d9cnqzbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fork-and-spoon" {...props}></Icon>
