<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nj_blobin.css';
import '../../css/o/o9g3uib3g.css';
import '../../css/r/r_8wvnbmq.css';
import '../../css/y/ybwdl8vbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="nj_blobin"/><path class="o9g3uib3g"/><path class="r_8wvnbmq"/><path class="ybwdl8vbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:cloud-refresh" {...props}></Icon>
