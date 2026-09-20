<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/lkm9t2bni.css';
import '../../css/r/rzk0jubzq.css';
import '../../css/u/ugibliw5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lkm9t2bni"/><path class="rzk0jubzq"/><path class="ugibliw5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plant-2-off" {...props}></Icon>
