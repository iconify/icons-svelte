<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vu7pc9bti.css';
import '../../css/d/dos_yhbgg.css';
import '../../css/d/dqapyabwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vu7pc9bti"/><circle class="dos_yhbgg"/><circle class="dqapyabwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:music-4" {...props}></Icon>
