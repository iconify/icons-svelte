<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc42tcp8f.css';
import '../../css/q/qol5o9b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xc42tcp8f"/><path class="qol5o9b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-pie-slice-48" {...props}></Icon>
