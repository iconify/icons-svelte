<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tagrm1y9i.css';
import '../../css/n/nl8u9ehql.css';
import '../../css/a/a_-f_rbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tagrm1y9i"/><path class="nl8u9ehql wm-a"/><path class="a_-f_rbjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:keyboard-duo" {...props}></Icon>
