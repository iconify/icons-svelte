<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpel3hezc.css';
import '../../css/h/h31m63bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tpel3hezc"/><path class="h31m63bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-line-48-bold" {...props}></Icon>
