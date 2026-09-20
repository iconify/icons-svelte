<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/p9-zrkb4g.css';
import '../../css/l/leu3_hbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p9-zrkb4g"/><path class="leu3_hbjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:dollar-circle-line" {...props}></Icon>
