<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pi3vdnbck.css';
import '../../css/b/byal82bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1503,"height":1504};
const content = `<g class="ft5dv1b6b"><path class="pi3vdnbck"/><path clip-rule="evenodd" class="byal82bxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avalanche" {...props}></Icon>
