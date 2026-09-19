<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mt34s3bhs.css';
import '../../css/v/vig5ljzia.css';
import '../../css/d/dm66__bjg.css';
import '../../css/b/bvfbpgyzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="mt34s3bhs"/><path class="vig5ljzia"/><path class="dm66__bjg"/><path class="bvfbpgyzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:alarm-clock-duo" {...props}></Icon>
