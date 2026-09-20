<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qrfysjbiw.css';
import '../../css/x/xvyoppupm.css';
import '../../css/b/bkp-5qvjz.css';
import '../../css/q/q5nvadb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<g class="ft5dv1b6b"><path class="qrfysjbiw"/><path class="xvyoppupm"/><path class="bkp-5qvjz"/><path class="q5nvadb_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:better-auth-dark" {...props}></Icon>
