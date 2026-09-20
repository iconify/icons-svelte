<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m8netx35k.css';
import '../../css/p/pve7dkb2j.css';
import '../../css/q/qgl0b2pvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m8netx35k"/><path class="pve7dkb2j"/><path class="qgl0b2pvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-shake-line-duotone" {...props}></Icon>
