<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxllr2mpy.css';
import '../../css/m/m60w9bg_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qxllr2mpy"/><path class="m60w9bg_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bearing-20-bold" {...props}></Icon>
