<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lydmw8yfb.css';
import '../../css/d/dtyb4zbgu.css';
import '../../css/y/yafmuequb.css';
import '../../css/f/fxqaxnipa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lydmw8yfb"/><path class="dtyb4zbgu wm-a"/><path class="wm-k yafmuequb"/><path class="fxqaxnipa wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:id-card-sketch" {...props}></Icon>
