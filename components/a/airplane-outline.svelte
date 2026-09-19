<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r06jb90lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r06jb90lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:airplane-outline" {...props}></Icon>
