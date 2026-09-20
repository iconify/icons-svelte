<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/olpk-abtk.css';
import '../../css/o/ohzrneb_u.css';
import '../../css/l/lq2ydebmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="olpk-abtk"/><path class="ohzrneb_u"/><path class="lq2ydebmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:battery-low" {...props}></Icon>
