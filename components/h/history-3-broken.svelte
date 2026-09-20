<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/ms8v4qbfc.css';
import '../../css/a/azv323yuq.css';
import '../../css/u/uqhik9b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ms8v4qbfc"/><path class="azv323yuq"/><path class="uqhik9b3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:history-3-broken" {...props}></Icon>
