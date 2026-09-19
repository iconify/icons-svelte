<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/b/bkgsdzb8x.css';
import '../../css/i/iuvgjdbsi.css';
import '../../css/j/jfdr82bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="bkgsdzb8x"/><path class="iuvgjdbsi"/><path class="jfdr82bgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-receive-01" {...props}></Icon>
