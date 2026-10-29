<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xtt1ysbre.css';
import '../../css/b/blzdo3hjo.css';
import '../../css/x/xyd9cyb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xtt1ysbre"/><path class="blzdo3hjo wm-shadow"/><path class="xyd9cyb9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:braces-engrave" {...props}></Icon>
