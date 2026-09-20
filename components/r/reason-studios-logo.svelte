<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/i/imdv_ebmd.css';
import '../../css/s/sxgmmi61m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="imdv_ebmd"/><path class="sxgmmi61m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:reason-studios-logo" {...props}></Icon>
