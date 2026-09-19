<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv4_thskj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nv4_thskj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mediafire" {...props}></Icon>
