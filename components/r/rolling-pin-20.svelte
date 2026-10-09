<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfsmapzzo.css';
import '../../css/v/vkz5pbbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bfsmapzzo"/><path class="vkz5pbbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rolling-pin-20" {...props}></Icon>
