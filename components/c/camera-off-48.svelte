<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvnxtwbjm.css';
import '../../css/a/aaaysobzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pvnxtwbjm"/><path class="aaaysobzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-off-48" {...props}></Icon>
