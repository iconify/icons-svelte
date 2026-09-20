<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r8ns4tb9k.css';
import '../../css/f/fue8kp0ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r8ns4tb9k"/><path class="fue8kp0ma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clear-day-duotone" {...props}></Icon>
