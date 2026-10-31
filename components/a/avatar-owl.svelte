<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i_etw1bgz.css';
import '../../css/k/kw_i36beb.css';
import '../../css/r/rogtb_2fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i_etw1bgz wm-k"/><path class="kw_i36beb wm-shine"/><path class="rogtb_2fk wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:avatar-owl" {...props}></Icon>
