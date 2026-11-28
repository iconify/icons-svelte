<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4x0e2ert.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t3zbr9bdz.css';
import '../../css/t/tvtinublm.css';
import '../../css/a/ards16uyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w4x0e2ert"/><g class="dt0cm9dhy primary"><path class="t3zbr9bdz"/><path class="tvtinublm"/><path class="ards16uyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:facebook-duo" {...props}></Icon>
