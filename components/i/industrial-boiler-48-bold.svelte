<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzeh33brv.css';
import '../../css/k/k2l56tbqb.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gzeh33brv"/><path class="k2l56tbqb"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:industrial-boiler-48-bold" {...props}></Icon>
