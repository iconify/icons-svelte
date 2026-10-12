<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmhcx3b_c.css';
import '../../css/k/kvl9ucc0s.css';
import '../../css/t/ttinssb5v.css';
import '../../css/e/ed4mxccbx.css';
import '../../css/e/eqdr87b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nmhcx3b_c"/><path class="kvl9ucc0s"/><path class="ttinssb5v"/><path class="ed4mxccbx"/><path class="eqdr87b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-x-20" {...props}></Icon>
