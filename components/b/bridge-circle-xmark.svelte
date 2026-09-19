<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv3slsasd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cv3slsasd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bridge-circle-xmark" {...props}></Icon>
