<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr3u_81nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dr3u_81nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:chain" {...props}></Icon>
