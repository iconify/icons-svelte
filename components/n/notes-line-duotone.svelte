<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/asw3fob5g.css';
import '../../css/z/zsc5-p0ft.css';
import '../../css/d/dnl23qbfb.css';
import '../../css/f/fxxrxhu1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="asw3fob5g"/><path class="zsc5-p0ft"/><path class="dnl23qbfb"/><path class="fxxrxhu1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notes-line-duotone" {...props}></Icon>
