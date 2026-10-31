<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/e-y2mtbbu.css';
import '../../css/d/dwmxtrzeo.css';
import '../../css/f/fap4nybrw.css';
import '../../css/i/ic2u5wcyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="e-y2mtbbu wm-shadow"/><path class="dwmxtrzeo wm-shadow"/><path class="fap4nybrw"/><path class="ic2u5wcyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:egg" {...props}></Icon>
