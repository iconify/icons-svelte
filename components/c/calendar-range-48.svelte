<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pycxs8orj.css';
import '../../css/o/oy7flk86j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="oy7flk86j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-range-48" {...props}></Icon>
