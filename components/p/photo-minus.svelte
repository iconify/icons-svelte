<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bezk08bnz.css';
import '../../css/h/hn7lp_bzn.css';
import '../../css/t/tu-453b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bezk08bnz"/><path class="hn7lp_bzn"/><path class="tu-453b3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-minus" {...props}></Icon>
