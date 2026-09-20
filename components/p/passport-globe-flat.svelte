<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r7it1xbry.css';
import '../../css/p/pdc-cheye.css';
import '../../css/g/gp9no01ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="r7it1xbry"/><path clip-rule="evenodd" class="pdc-cheye"/><path class="gp9no01ex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:passport-globe-flat" {...props}></Icon>
