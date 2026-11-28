<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiaedibfv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dca2urprn.css';
import '../../css/t/t-hhzbcli.css';
import '../../css/n/np8nxgbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xiaedibfv"/><g class="dt0cm9dhy primary"><path class="dca2urprn"/><path class="t-hhzbcli"/><path class="np8nxgbar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:doorbell-duo" {...props}></Icon>
