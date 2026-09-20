<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s-q_p4biq.css';
import '../../css/x/xf83swd9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s-q_p4biq"/><path class="xf83swd9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:edit-detailed-alt-duotone" {...props}></Icon>
