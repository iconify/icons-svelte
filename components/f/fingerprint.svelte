<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rtlatxgqd.css';
import '../../css/m/mzwrmz51p.css';
import '../../css/v/vg3q4ac4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rtlatxgqd"/><path class="mzwrmz51p"/><path class="vg3q4ac4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fingerprint" {...props}></Icon>
