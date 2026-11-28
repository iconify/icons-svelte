<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhtj_xbkr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qqs5wqj6r.css';
import '../../css/h/huc2a6r5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhtj_xbkr secondary"/><g class="dt0cm9dhy primary"><path class="qqs5wqj6r"/><path class="huc2a6r5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:container-duo" {...props}></Icon>
