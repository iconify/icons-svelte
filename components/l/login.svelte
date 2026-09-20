<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/st3a4ib_h.css';
import '../../css/d/dv4gr9bmd.css';
import '../../css/h/hav7c1hub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="st3a4ib_h"/><path class="dv4gr9bmd"/><path class="hav7c1hub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:login" {...props}></Icon>
