<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bxiujei5b.css';
import '../../css/q/qrlq0qbok.css';
import '../../css/s/s7vwfzb4c.css';
import '../../css/d/d0tiy9blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bxiujei5b"/><path class="qrlq0qbok wm-k"/><path class="s7vwfzb4c wm-a"/><path class="d0tiy9blv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-down-sketch" {...props}></Icon>
