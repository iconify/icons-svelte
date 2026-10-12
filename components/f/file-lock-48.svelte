<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9uhwm-oy.css';
import '../../css/p/p6h1q_4_y.css';
import '../../css/w/wweom8b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a9uhwm-oy"/><path class="p6h1q_4_y"/><path class="wweom8b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-lock-48" {...props}></Icon>
