<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8n0vpbri.css';
import '../../css/a/apu5ltb_q.css';
import '../../css/i/i49k2acdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j8n0vpbri"/><path class="apu5ltb_q"/><path class="i49k2acdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onlyoffice-light" {...props}></Icon>
