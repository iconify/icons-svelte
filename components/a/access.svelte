<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nc23yw7-v.css';
import '../../css/m/m24ig1bjm.css';
import '../../css/w/w_x3o7r4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nc23yw7-v"/><path class="m24ig1bjm"/><path class="w_x3o7r4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:access" {...props}></Icon>
