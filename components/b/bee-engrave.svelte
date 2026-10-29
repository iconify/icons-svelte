<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sfjcrxw8m.css';
import '../../css/e/elmzdpb0f.css';
import '../../css/d/d1xkg3smp.css';
import '../../css/f/fateqpjcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sfjcrxw8m"/><path class="elmzdpb0f wm-shadow"/><path class="d1xkg3smp"/><path class="fateqpjcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bee-engrave" {...props}></Icon>
