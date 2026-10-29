<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/ws3h1mbaj.css';
import '../../css/y/ygx-4bbhz.css';
import '../../css/c/cdh3yqz5n.css';
import '../../css/z/znt-8tb8p.css';
import '../../css/k/k9yaaohqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k ws3h1mbaj"/><path class="wm-s ygx-4bbhz"/><path class="cdh3yqz5n wm-shadow"/><path class="wm-k znt-8tb8p"/><path class="k9yaaohqa wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-off-engrave" {...props}></Icon>
