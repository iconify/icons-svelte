<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_z99bhx.css';
import '../../css/w/wkx6n0o2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ca_z99bhx"/><path class="wkx6n0o2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:invoice-48" {...props}></Icon>
