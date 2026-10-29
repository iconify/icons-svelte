<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qpl6hxb8w.css';
import '../../css/j/ji6eupbux.css';
import '../../css/y/y63n77z1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qpl6hxb8w"/><path class="ji6eupbux wm-shadow"/><path class="y63n77z1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gift-stack-engrave" {...props}></Icon>
