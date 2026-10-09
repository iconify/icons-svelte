<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbbi_6vwc.css';
import '../../css/x/xo70x1c7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qbbi_6vwc"/><path class="xo70x1c7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:music-20-bold" {...props}></Icon>
