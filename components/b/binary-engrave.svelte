<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cw-__yysm.css';
import '../../css/e/eur2u4bcy.css';
import '../../css/c/c9dpx0b6e.css';
import '../../css/j/j3cn9rb9q.css';
import '../../css/b/bq7bz5b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cw-__yysm wm-k"/><path class="eur2u4bcy wm-a"/><path class="c9dpx0b6e wm-shadow"/><path class="j3cn9rb9q wm-k"/><path class="bq7bz5b6b wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:binary-engrave" {...props}></Icon>
