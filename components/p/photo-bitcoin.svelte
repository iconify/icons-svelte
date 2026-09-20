<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n_hes3sdi.css';
import '../../css/f/f2y748k3o.css';
import '../../css/n/nq-mj83lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_hes3sdi"/><path class="f2y748k3o"/><path class="nq-mj83lp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-bitcoin" {...props}></Icon>
