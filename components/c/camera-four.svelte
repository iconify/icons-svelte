<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/m/m_vk58bve.css';
import '../../css/m/m_9bs70wo.css';
import '../../css/z/zjedaobvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="m_vk58bve"/><path class="m_9bs70wo"/><path class="zjedaobvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:camera-four" {...props}></Icon>
