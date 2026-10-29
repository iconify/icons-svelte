<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nzo06bbex.css';
import '../../css/t/t1wbj0d5e.css';
import '../../css/i/icn4j_bqy.css';
import '../../css/a/avgg4ibne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nzo06bbex wm-k"/><path class="t1wbj0d5e wm-a"/><path class="icn4j_bqy wm-k"/><path class="avgg4ibne wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:citrus-sketch" {...props}></Icon>
