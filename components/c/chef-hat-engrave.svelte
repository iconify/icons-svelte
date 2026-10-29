<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hlqfty9am.css';
import '../../css/q/q1zsas24y.css';
import '../../css/b/b4x7prkcu.css';
import '../../css/t/te682eb5s.css';
import '../../css/y/yqkivob1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hlqfty9am wm-k"/><path class="q1zsas24y wm-a"/><path class="b4x7prkcu wm-shadow"/><path class="te682eb5s wm-k"/><path class="wm-a yqkivob1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chef-hat-engrave" {...props}></Icon>
