<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bmrn8acqb.css';
import '../../css/l/lww7c4bwc.css';
import '../../css/x/xbqzh6bgi.css';
import '../../css/s/smie_ib3h.css';
import '../../css/q/qso6odhhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bmrn8acqb"/><path class="lww7c4bwc"/><path class="xbqzh6bgi"/><path class="smie_ib3h"/><path class="qso6odhhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gate-nor" {...props}></Icon>
