<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pycxs8orj.css';
import '../../css/k/kdnqzpb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="kdnqzpb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-star-48" {...props}></Icon>
