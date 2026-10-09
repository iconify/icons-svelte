<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ebr9bjc.css';
import '../../css/u/ufscmvy2b.css';
import '../../css/v/vslp_-0hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p5ebr9bjc"/><path class="ufscmvy2b"/><path class="vslp_-0hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-refuelling-48" {...props}></Icon>
