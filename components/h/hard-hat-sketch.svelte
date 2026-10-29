<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i83db182z.css';
import '../../css/d/dwsa8ob3o.css';
import '../../css/p/p0cq4h5-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i83db182z wm-a"/><path class="dwsa8ob3o wm-k"/><path class="p0cq4h5-v wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hard-hat-sketch" {...props}></Icon>
