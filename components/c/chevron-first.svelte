<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bc6ll9ksr.css';
import '../../css/n/nd4_eabip.css';
import '../../css/n/ngiiyccfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bc6ll9ksr wm-shadow"/><path class="nd4_eabip wm-shadow"/><path class="ngiiyccfa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chevron-first" {...props}></Icon>
