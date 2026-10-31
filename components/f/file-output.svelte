<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/r9px29bcq.css';
import '../../css/l/lou_evkxu.css';
import '../../css/u/ucnad0gku.css';
import '../../css/m/mkl7_9b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="r9px29bcq wm-shadow"/><path class="lou_evkxu wm-shadow"/><path class="ucnad0gku"/><path class="mkl7_9b_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:file-output" {...props}></Icon>
