<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lngcvmxva.css';
import '../../css/c/cl68f3slr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lngcvmxva"/><path class="cl68f3slr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pink-heart" {...props}></Icon>
