<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiod-8bbi.css';
import '../../css/k/kq1tsebcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qiod-8bbi"/><path class="kq1tsebcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-mcs-48-bold" {...props}></Icon>
