<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkkz-bboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dkkz-bboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffee-mug" {...props}></Icon>
