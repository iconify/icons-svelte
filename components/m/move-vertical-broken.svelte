<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qavqpjbpl.css';
import '../../css/m/mdiuojfnf.css';
import '../../css/g/g92_1ls8c.css';
import '../../css/q/q-d3abbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qavqpjbpl"/><path class="mdiuojfnf"/><path class="g92_1ls8c"/><path class="q-d3abbgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-vertical-broken" {...props}></Icon>
