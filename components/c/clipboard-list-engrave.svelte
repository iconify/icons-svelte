<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/ltmr-acea.css';
import '../../css/b/b3lg4q9xa.css';
import '../../css/j/jsy_ccc8l.css';
import '../../css/m/mzsw-jb7t.css';
import '../../css/k/kiwgpqb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ltmr-acea wm-k"/><path class="b3lg4q9xa wm-a"/><path class="jsy_ccc8l wm-shadow"/><path class="mzsw-jb7t wm-k"/><path class="kiwgpqb3o wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clipboard-list-engrave" {...props}></Icon>
