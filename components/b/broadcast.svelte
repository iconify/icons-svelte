<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/ysf7mbcrq.css';
import '../../css/y/y0gk63t6x.css';
import '../../css/g/gz5_swrdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ysf7mbcrq"/><path class="y0gk63t6x"/><path class="gz5_swrdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:broadcast" {...props}></Icon>
