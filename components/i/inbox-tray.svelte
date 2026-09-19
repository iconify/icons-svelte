<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cw7t2ddpt.css';
import '../../css/t/tpuop0bqq.css';
import '../../css/o/oa4z7jbas.css';
import '../../css/l/lkbnzpjnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cw7t2ddpt"/><path class="tpuop0bqq"/><path class="oa4z7jbas"/><path class="lkbnzpjnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:inbox-tray" {...props}></Icon>
