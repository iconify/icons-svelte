<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edwtppbpi.css';
import '../../css/y/yuuekixxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="edwtppbpi"/><path class="yuuekixxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-plane-48" {...props}></Icon>
