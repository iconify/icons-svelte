<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy8v7obgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gy8v7obgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:jcl" {...props}></Icon>
