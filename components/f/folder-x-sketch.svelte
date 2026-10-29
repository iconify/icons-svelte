<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b9avuib2m.css';
import '../../css/d/d8myy4w_r.css';
import '../../css/o/ox-wivbrj.css';
import '../../css/z/zzy48nbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b9avuib2m"/><path class="d8myy4w_r wm-a"/><path class="ox-wivbrj wm-k"/><path class="wm-a zzy48nbew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-x-sketch" {...props}></Icon>
