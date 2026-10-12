<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhfn3yyhb.css';
import '../../css/o/of8os1b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mhfn3yyhb"/><path class="of8os1b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:owl-20" {...props}></Icon>
