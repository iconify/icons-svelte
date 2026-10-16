<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jha4hptgn.css';
import '../../css/u/uq6wzpn-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jha4hptgn"/><path class="uq6wzpn-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-alert-48" {...props}></Icon>
