<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/h/h22q30bqx.css';
import '../../css/s/s6tfabbgr.css';
import '../../css/u/u9l6lfbri.css';
import '../../css/h/hjmtsxb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="h22q30bqx wm-shadow"/><path class="s6tfabbgr wm-shadow"/><path class="u9l6lfbri"/><path class="hjmtsxb_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:house-wifi" {...props}></Icon>
