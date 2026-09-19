<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/b/bj-pxl6bp.css';
import '../../css/u/uue630blk.css';
import '../../css/p/pm7666zog.css';
import '../../css/g/g5y4hzclc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path class="bj-pxl6bp"/><path class="uue630blk"/><path class="pm7666zog"/><path class="g5y4hzclc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bottle-one" {...props}></Icon>
