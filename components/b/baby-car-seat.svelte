<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/m16iq-bli.css';
import '../../css/h/h93505_yx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMFckIcYW"><g class="v3_i3wktz"><path class="m16iq-bli"/><path class="h93505_yx"/></g></mask></defs><path mask="url(#SVGMFckIcYW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:baby-car-seat" {...props}></Icon>
