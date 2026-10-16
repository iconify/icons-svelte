<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_epzybyz.css';
import '../../css/i/ihy07ry6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r_epzybyz"/><path class="ihy07ry6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-hybrid-48-bold" {...props}></Icon>
