<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/dvssgz61n.css';
import '../../css/e/enu23zbgq.css';
import '../../css/p/parzbjbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dvssgz61n"/><path class="enu23zbgq"/><path class="parzbjbsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-notion" {...props}></Icon>
