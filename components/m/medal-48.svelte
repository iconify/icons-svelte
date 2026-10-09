<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8ovs__gx.css';
import '../../css/b/bhg_0dbbc.css';
import '../../css/y/yhupigbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y8ovs__gx"/><path class="bhg_0dbbc"/><path class="yhupigbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:medal-48" {...props}></Icon>
