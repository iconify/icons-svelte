<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k6y8f8bcv.css';
import '../../css/r/rk0e0ccfm.css';
import '../../css/c/cewph5ymu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":160,"height":160};
const content = `<g class="ft5dv1b6b"><path class="k6y8f8bcv"/><path class="rk0e0ccfm"/><path class="cewph5ymu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bytebase" {...props}></Icon>
