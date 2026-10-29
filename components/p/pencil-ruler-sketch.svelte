<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uivb_ubdk.css';
import '../../css/v/v55zsebyu.css';
import '../../css/q/q6z6ai9lv.css';
import '../../css/v/vkq-kzxjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uivb_ubdk"/><path class="v55zsebyu wm-a"/><path class="q6z6ai9lv wm-k"/><path class="vkq-kzxjk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pencil-ruler-sketch" {...props}></Icon>
