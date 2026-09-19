<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnii4hccr.css';
import '../../css/s/sozjgdcyd.css';
import '../../css/x/xfox-b84f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="rnii4hccr"/><circle class="sozjgdcyd"/><path class="xfox-b84f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:help-buoy-outline" {...props}></Icon>
