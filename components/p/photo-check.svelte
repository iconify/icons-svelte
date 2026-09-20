<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/ea4hx2bih.css';
import '../../css/h/hn7lp_bzn.css';
import '../../css/q/qf20nh9zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ea4hx2bih"/><path class="hn7lp_bzn"/><path class="qf20nh9zn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-check" {...props}></Icon>
