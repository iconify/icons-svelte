<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/ea_31gbnm.css';
import '../../css/u/u9_hwpzmi.css';
import '../../css/v/vnsop5_4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ea_31gbnm"/><path class="u9_hwpzmi"/><path class="vnsop5_4w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-library-line-duotone" {...props}></Icon>
