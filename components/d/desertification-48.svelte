<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwg1c_b8g.css';
import '../../css/v/vy6oo5ohm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bwg1c_b8g"/><path class="vy6oo5ohm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desertification-48" {...props}></Icon>
