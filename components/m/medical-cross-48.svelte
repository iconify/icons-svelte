<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kirv6-xpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kirv6-xpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:medical-cross-48" {...props}></Icon>
