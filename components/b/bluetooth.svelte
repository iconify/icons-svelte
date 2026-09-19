<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgpyz9bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hgpyz9bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bluetooth" {...props}></Icon>
