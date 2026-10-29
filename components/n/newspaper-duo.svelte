<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/luvu58brr.css';
import '../../css/l/l4ok05b1o.css';
import '../../css/b/b55os-lyu.css';
import '../../css/b/bkk0xnbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="luvu58brr"/><path class="l4ok05b1o wm-a"/><path class="b55os-lyu"/><path class="bkk0xnbka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:newspaper-duo" {...props}></Icon>
