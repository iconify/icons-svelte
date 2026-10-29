<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j7y3a7bgh.css';
import '../../css/s/sliiisb3g.css';
import '../../css/v/v8clh90yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j7y3a7bgh"/><path class="sliiisb3g wm-shadow"/><path class="v8clh90yn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gift-engrave" {...props}></Icon>
