<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kimfu9q5t.css';
import '../../css/p/p_z32__tj.css';
import '../../css/a/an10mdq2o.css';
import '../../css/v/vl729ybrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kimfu9q5t"/><path class="p_z32__tj"/><path class="an10mdq2o"/><path class="vl729ybrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-spreadsheet-20" {...props}></Icon>
