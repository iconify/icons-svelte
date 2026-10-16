<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vu7zgc8gt.css';
import '../../css/d/dqapyabwu.css';
import '../../css/t/tke4h5b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vu7zgc8gt"/><circle class="dqapyabwu"/><circle class="tke4h5b0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:eighth-notes" {...props}></Icon>
