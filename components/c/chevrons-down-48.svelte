<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgbrg5b8n.css';
import '../../css/c/cw3c7_bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xgbrg5b8n"/><path class="cw3c7_bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-down-48" {...props}></Icon>
