<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/rjfa5r6oo.css';
import '../../css/r/ryfnj1b-x.css';
import '../../css/c/chbn-o-on.css';
import '../../css/h/hfvrmofqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="rjfa5r6oo wm-shadow"/><path class="ryfnj1b-x wm-shadow"/><path class="chbn-o-on"/><path class="hfvrmofqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:pound-sterling" {...props}></Icon>
