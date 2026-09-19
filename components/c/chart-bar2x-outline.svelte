<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbv56ac9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vbv56ac9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-bar2x-outline" {...props}></Icon>
