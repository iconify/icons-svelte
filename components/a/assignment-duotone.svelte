<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/afpnkyb_h.css';
import '../../css/k/kvcl3e-we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="afpnkyb_h"/><path class="kvcl3e-we"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:assignment-duotone" {...props}></Icon>
