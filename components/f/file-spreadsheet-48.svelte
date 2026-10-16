<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dezwopb-j.css';
import '../../css/i/im6_9vhgw.css';
import '../../css/r/rfgrjcbjr.css';
import '../../css/q/qel2yy7gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="im6_9vhgw"/><path class="rfgrjcbjr"/><path class="qel2yy7gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-spreadsheet-48" {...props}></Icon>
