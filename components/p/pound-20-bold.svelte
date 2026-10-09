<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt8f97bci.css';
import '../../css/x/xyx_nmb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qt8f97bci"/><path class="xyx_nmb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pound-20-bold" {...props}></Icon>
