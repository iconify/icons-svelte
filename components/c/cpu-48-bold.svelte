<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdierubwu.css';
import '../../css/t/tte9pybuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jdierubwu"/><path class="tte9pybuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cpu-48-bold" {...props}></Icon>
