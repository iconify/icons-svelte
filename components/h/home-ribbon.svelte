<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/r_hrkacfe.css';
import '../../css/f/fj12aacni.css';
import '../../css/n/n2hwc4qgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r_hrkacfe"/><path class="fj12aacni"/><path class="n2hwc4qgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:home-ribbon" {...props}></Icon>
