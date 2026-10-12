<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uqd0fzcso.css';
import '../../css/a/a92oxlbtb.css';
import '../../css/z/zmz7s-z1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uqd0fzcso"/><path class="a92oxlbtb"/><path class="zmz7s-z1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ethernet-port-duotone" {...props}></Icon>
