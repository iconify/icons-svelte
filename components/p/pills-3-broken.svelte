<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j5--7lgaw.css';
import '../../css/y/yc8xgkbyw.css';
import '../../css/p/pqsrmgrdx.css';
import '../../css/h/hqsaabc6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j5--7lgaw"/><path class="yc8xgkbyw"/><path class="pqsrmgrdx"/><path class="hqsaabc6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pills-3-broken" {...props}></Icon>
