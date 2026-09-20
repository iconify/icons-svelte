<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cukg2h6lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cukg2h6lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:5-plus" {...props}></Icon>
