<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wg6_qcb0k.css';
import '../../css/g/gazrs25wr.css';
import '../../css/p/p56g1hbvw.css';
import '../../css/r/r-1hfob1v.css';
import '../../css/g/gey1o-bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wg6_qcb0k"/><path class="gazrs25wr"/><path class="p56g1hbvw"/><path clip-rule="evenodd" class="r-1hfob1v"/><path class="gey1o-bbf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:laptop" {...props}></Icon>
