<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dwuaxabbb.css';
import '../../css/p/pk03-9beu.css';
import '../../css/z/z_02kkxdd.css';
import '../../css/u/uh6a78blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dwuaxabbb wm-k"/><path class="pk03-9beu wm-shadow"/><path class="wm-k z_02kkxdd"/><path class="uh6a78blk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:book-open-check-engrave" {...props}></Icon>
