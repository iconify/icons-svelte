<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d7kxs_g1s.css';
import '../../css/n/n35dlibfy.css';
import '../../css/d/dyzbezbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d7kxs_g1s"/><path class="n35dlibfy"/><path class="dyzbezbug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:location-pin-off-duotone" {...props}></Icon>
