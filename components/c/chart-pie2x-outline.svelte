<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msnimri5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="msnimri5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-pie2x-outline" {...props}></Icon>
