<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_xunsc5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z_xunsc5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:plane" {...props}></Icon>
