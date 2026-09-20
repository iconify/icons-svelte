<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q8rdncb-p.css';
import '../../css/u/uerxq0b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q8rdncb-p"/><path class="uerxq0b_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dashboard-duotone" {...props}></Icon>
