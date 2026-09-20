<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/ho-7xdd0k.css';
import '../../css/q/qnpvard1a.css';
import '../../css/w/wcs8p4ttm.css';
import '../../css/r/r8rap4b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ho-7xdd0k"/><path class="qnpvard1a"/><path class="wcs8p4ttm"/><path class="r8rap4b0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-call-line-duotone" {...props}></Icon>
