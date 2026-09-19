<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4k3to8hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r4k3to8hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:binoculars" {...props}></Icon>
