<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw9nxhb5q.css';
import '../../css/a/aet2f2bmc.css';
import '../../css/i/ikpbwe38b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gw9nxhb5q"/><path class="aet2f2bmc"/><path class="ikpbwe38b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:generator-alert-48" {...props}></Icon>
