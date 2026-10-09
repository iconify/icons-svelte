<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd0toxw3n.css';
import '../../css/e/e_hc3taxx.css';
import '../../css/f/fz88cgg4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gd0toxw3n"/><path class="e_hc3taxx"/><path class="fz88cgg4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:log-out-20" {...props}></Icon>
