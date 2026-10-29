<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yqikedbdt.css';
import '../../css/z/zntvhn8qg.css';
import '../../css/p/pk03-9beu.css';
import '../../css/c/ctjcreb2q.css';
import '../../css/l/levrdiinv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k yqikedbdt"/><path class="wm-a zntvhn8qg"/><path class="pk03-9beu wm-shadow"/><path class="ctjcreb2q wm-k"/><path class="levrdiinv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:book-open-text-engrave" {...props}></Icon>
