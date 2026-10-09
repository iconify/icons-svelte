<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx2xmtbjn.css';
import '../../css/p/pbe7yvb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xx2xmtbjn"/><path class="pbe7yvb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-down-square-48" {...props}></Icon>
