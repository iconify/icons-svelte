<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/is9k_idfr.css';
import '../../css/i/igs6bnbke.css';
import '../../css/k/kil06obbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="is9k_idfr"/><path class="igs6bnbke"/><path class="kil06obbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:podcast-sharp-duotone" {...props}></Icon>
