<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rqv1gomtd.css';
import '../../css/t/t0j7vybue.css';
import '../../css/a/aqe47bbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rqv1gomtd"/><path clip-rule="evenodd" class="t0j7vybue"/><path class="aqe47bbrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bank" {...props}></Icon>
