<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vfhc6tbph.css';
import '../../css/q/qrlzx4l6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vfhc6tbph"/><path class="qrlzx4l6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:crosshair-detailed-duotone" {...props}></Icon>
