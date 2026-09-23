<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/jlo57kb2p.css';
import '../../css/f/flz8mqbuo.css';
import '../../css/e/euvx74byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jlo57kb2p"/><path class="flz8mqbuo"/><path class="euvx74byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gift-sparkles-sharp-duotone" {...props}></Icon>
