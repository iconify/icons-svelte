<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h55xb4bob.css';
import '../../css/v/vtxvw3bnv.css';
import '../../css/o/ows-rgbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h55xb4bob"/><path class="vtxvw3bnv"/><path class="ows-rgbwf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gps-off-02" {...props}></Icon>
