<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr272q-zt.css';
import '../../css/m/mhc-hp51p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<circle class="wr272q-zt"/><path class="mhc-hp51p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:chrome-wordmark" {...props}></Icon>
