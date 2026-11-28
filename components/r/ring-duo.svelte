<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao03dfw0g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/ksjg_ccnr.css';
import '../../css/r/r66u58wsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao03dfw0g secondary"/><g class="dt0cm9dhy primary"><path class="ksjg_ccnr"/><path class="r66u58wsc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ring-duo" {...props}></Icon>
