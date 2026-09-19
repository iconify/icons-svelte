<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0g1hvbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p0g1hvbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:erase" {...props}></Icon>
