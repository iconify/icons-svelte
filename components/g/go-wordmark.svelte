<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nibs_lbmi.css';
import '../../css/a/as15v3bwn.css';
import '../../css/q/qrc405bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="nibs_lbmi"><path class="as15v3bwn"/><path class="qrc405bkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:go-wordmark" {...props}></Icon>
