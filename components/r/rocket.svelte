<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/f/fl78u9b5f.css';
import '../../css/v/v38uq9ztf.css';
import '../../css/m/m41g8eioq.css';
import '../../css/g/g71l8mfcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="fl78u9b5f"/><path class="v38uq9ztf wm-shine"/><path class="m41g8eioq wm-k"/><path class="g71l8mfcw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:rocket" {...props}></Icon>
