<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwyivikpc.css';
import '../../css/m/mdo2xzb3k.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wwyivikpc"/><path class="mdo2xzb3k"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-holder-48-bold" {...props}></Icon>
