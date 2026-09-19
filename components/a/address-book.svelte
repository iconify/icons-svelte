<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t68u_vbpr.css';
import '../../css/c/cs3fob1lr.css';
import '../../css/w/wfz41fcby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t68u_vbpr"/><path class="cs3fob1lr"/><path class="wfz41fcby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:address-book" {...props}></Icon>
