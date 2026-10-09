<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pycxs8orj.css';
import '../../css/w/w941f1b7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="w941f1b7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-days-48" {...props}></Icon>
