<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/woph2abqr.css';
import '../../css/f/fedm_ccnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="woph2abqr"/><path class="fedm_ccnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:map-duotone" {...props}></Icon>
