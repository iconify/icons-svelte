<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x0yz31lpp.css';
import '../../css/f/f91o_cxsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x0yz31lpp"/><path class="f91o_cxsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hammer-alt-duotone" {...props}></Icon>
