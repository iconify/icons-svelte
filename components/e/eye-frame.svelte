<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nworg_q_t.css';
import '../../css/x/xspw_mt-i.css';
import '../../css/e/ecwads5ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="nworg_q_t"/><path class="xspw_mt-i"/><path class="ecwads5ve"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:eye-frame" {...props}></Icon>
