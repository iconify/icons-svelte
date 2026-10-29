<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dnhfhj4qr.css';
import '../../css/a/azhil-l4y.css';
import '../../css/g/ganinvb3m.css';
import '../../css/z/zpodnwj0o.css';
import '../../css/s/s37zulbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dnhfhj4qr wm-k"/><path class="azhil-l4y wm-a"/><path class="ganinvb3m wm-shadow"/><path class="wm-k zpodnwj0o"/><path class="s37zulbpr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bed-engrave" {...props}></Icon>
