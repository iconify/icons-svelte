<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqjtt0biw.css';
import '../../css/u/up2-7-ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zqjtt0biw"/><path class="up2-7-ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biofuel-48" {...props}></Icon>
