<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkmlt_lmx.css';
import '../../css/m/m4o-xp_cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hkmlt_lmx"/><path class="m4o-xp_cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nozzle-20" {...props}></Icon>
