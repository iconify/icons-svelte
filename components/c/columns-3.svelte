<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/g/gvys7u6cq.css';
import '../../css/x/xasz54-bm.css';
import '../../css/k/kjkbr1xrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="gvys7u6cq"/><path class="xasz54-bm"/><path class="kjkbr1xrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:columns-3" {...props}></Icon>
