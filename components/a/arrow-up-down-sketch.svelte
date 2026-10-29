<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qygg6abkf.css';
import '../../css/h/h42k6-b2l.css';
import '../../css/v/vd6ip0kos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qygg6abkf wm-a"/><path class="h42k6-b2l wm-k"/><path class="vd6ip0kos wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-up-down-sketch" {...props}></Icon>
