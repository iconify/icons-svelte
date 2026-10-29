<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/dt3yg1qsa.css';
import '../../css/t/tsa86mbae.css';
import '../../css/y/ywk5os59u.css';
import '../../css/y/ywlhoqbsn.css';
import '../../css/k/k26yyvc5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="dt3yg1qsa wm-deco"/><path class="tsa86mbae wm-deco"/><path class="wm-deco ywk5os59u"/><path class="wm-k ywlhoqbsn"/><path class="k26yyvc5e wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:footprints-blueprint" {...props}></Icon>
