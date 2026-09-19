<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zfxrd8b9z.css';
import '../../css/i/i8n6q-sjq.css';
import '../../css/m/mv-txmbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zfxrd8b9z"/><path class="i8n6q-sjq"/><path class="mv-txmbcc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:passport-valid" {...props}></Icon>
