<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f7empmbbr.css';
import '../../css/o/oc0vi5bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f7empmbbr"/><path class="oc0vi5bvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:microphone-off-light" {...props}></Icon>
