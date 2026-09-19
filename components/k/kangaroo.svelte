<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h7yrl6lbb.css';
import '../../css/w/w6xc5vbzb.css';
import '../../css/r/rf_lmqdyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h7yrl6lbb"/><path class="w6xc5vbzb"/><path class="rf_lmqdyt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:kangaroo" {...props}></Icon>
