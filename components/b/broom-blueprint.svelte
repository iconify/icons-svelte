<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lhnaep5ah.css';
import '../../css/k/kya_atw0f.css';
import '../../css/a/aoozyu66l.css';
import '../../css/x/xl4x9fb_h.css';
import '../../css/z/zn_5tzyza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lhnaep5ah wm-deco"/><path class="kya_atw0f wm-deco"/><path class="aoozyu66l wm-k"/><path class="wm-a xl4x9fb_h"/><path class="wm-a zn_5tzyza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:broom-blueprint" {...props}></Icon>
