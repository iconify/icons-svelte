<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/k5rty6s-p.css';
import '../../css/k/kl46ljbgy.css';
import '../../css/z/zlaspxbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k5rty6s-p"/><path class="kl46ljbgy"/><path class="zlaspxbje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-sparkles-sharp-two-tone" {...props}></Icon>
