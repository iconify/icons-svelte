<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogczzsh5u.css';
import '../../css/n/nksap4bll.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ogczzsh5u"/><path class="nksap4bll"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-sphere-48-bold" {...props}></Icon>
