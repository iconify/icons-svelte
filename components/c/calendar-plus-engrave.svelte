<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/if8ytha7e.css';
import '../../css/j/jalfqco1n.css';
import '../../css/a/aari1qi6v.css';
import '../../css/j/jmvv3kbnk.css';
import '../../css/b/b091wry5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="if8ytha7e wm-k"/><path class="jalfqco1n wm-a"/><path class="aari1qi6v wm-shadow"/><path class="jmvv3kbnk wm-k"/><path class="b091wry5w wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-plus-engrave" {...props}></Icon>
