<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xddux4bha.css';
import '../../css/z/zgdn5--dp.css';
import '../../css/i/ii4v6lf-c.css';
import '../../css/v/v9wyovbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xddux4bha"/><path class="wm-a zgdn5--dp"/><path class="ii4v6lf-c wm-k"/><path class="v9wyovbbf wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:archive-sketch" {...props}></Icon>
