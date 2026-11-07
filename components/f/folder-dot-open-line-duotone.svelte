<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ieg6afw1p.css';
import '../../css/x/xz914h8mb.css';
import '../../css/z/zjtb9sbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ieg6afw1p"/><path class="xz914h8mb"/><path class="zjtb9sbmg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-dot-open-line-duotone" {...props}></Icon>
