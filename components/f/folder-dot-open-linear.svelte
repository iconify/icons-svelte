<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nq3ucobtl.css';
import '../../css/x/xz914h8mb.css';
import '../../css/z/zn-yurbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nq3ucobtl"/><path class="xz914h8mb"/><path class="zn-yurbog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-dot-open-linear" {...props}></Icon>
