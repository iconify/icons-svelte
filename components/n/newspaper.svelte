<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b55os-lyu.css';
import '../../css/b/bkk0xnbka.css';
import '../../css/l/l4ok05b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b55os-lyu"/><path class="bkk0xnbka"/><path class="l4ok05b1o wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:newspaper" {...props}></Icon>
