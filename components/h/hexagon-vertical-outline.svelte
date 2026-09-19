<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq6pc5b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zq6pc5b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hexagon-vertical-outline" {...props}></Icon>
