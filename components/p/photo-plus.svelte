<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/j6y2_1bpz.css';
import '../../css/h/hn7lp_bzn.css';
import '../../css/s/slfr0rbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j6y2_1bpz"/><path class="hn7lp_bzn"/><path class="slfr0rbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-plus" {...props}></Icon>
