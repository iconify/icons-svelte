<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/r8jruljur.css';
import '../../css/p/pth4tz50t.css';
import '../../css/g/gsomp2blf.css';
import '../../css/m/mzrr-bc3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="r8jruljur wm-shadow"/><path class="pth4tz50t wm-shadow"/><path class="gsomp2blf"/><path class="mzrr-bc3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:gallery-horizontal" {...props}></Icon>
