<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/s05pz4b9w.css';
import '../../css/d/dos_yhbgg.css';
import '../../css/d/dqapyabwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s05pz4b9w"/><circle class="dos_yhbgg"/><circle class="dqapyabwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:music" {...props}></Icon>
