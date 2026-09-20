<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukvxj4v6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ukvxj4v6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cairn-and-two-tall-rectangles-top-left" {...props}></Icon>
