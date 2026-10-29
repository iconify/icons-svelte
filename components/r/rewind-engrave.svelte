<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dtuw77bny.css';
import '../../css/a/ak_kr_1qo.css';
import '../../css/n/no_pq6-6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dtuw77bny"/><path class="ak_kr_1qo wm-shadow"/><path class="no_pq6-6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rewind-engrave" {...props}></Icon>
