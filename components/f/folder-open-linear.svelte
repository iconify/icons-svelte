<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nq3ucobtl.css';
import '../../css/j/j8r4okiod.css';
import '../../css/x/xz914h8mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nq3ucobtl"/><path class="j8r4okiod"/><path class="xz914h8mb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-open-linear" {...props}></Icon>
