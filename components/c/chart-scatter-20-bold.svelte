<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd5r-ktwc.css';
import '../../css/u/u81anactb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qd5r-ktwc"/><path class="u81anactb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-scatter-20-bold" {...props}></Icon>
