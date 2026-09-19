<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy--hfb3b.css';
import '../../css/d/dc1zo4nmc.css';
import '../../css/a/a9d8_nbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jy--hfb3b"/><path class="dc1zo4nmc"/><path class="a9d8_nbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-z-cloud-mod-stack" {...props}></Icon>
