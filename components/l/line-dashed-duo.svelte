<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lnsnpcbvi.css';
import '../../css/a/aq6xpmbtf.css';
import '../../css/s/stp3nf4wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lnsnpcbvi"/><path class="aq6xpmbtf"/><path class="stp3nf4wl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:line-dashed-duo" {...props}></Icon>
