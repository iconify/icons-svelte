<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/q/qc9puxbvd.css';
import '../../css/i/iqcv3-mbo.css';
import '../../css/k/koy68obkn.css';
import '../../css/j/jqoywtypg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="qc9puxbvd wm-shadow"/><path class="iqcv3-mbo wm-shadow"/><path class="koy68obkn"/><path class="jqoywtypg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chart-area" {...props}></Icon>
