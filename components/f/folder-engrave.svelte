<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/ui_oqub5z.css';
import '../../css/y/y_jfvcwtp.css';
import '../../css/l/l484bmbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ui_oqub5z"/><path class="wm-shadow y_jfvcwtp"/><path class="l484bmbsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-engrave" {...props}></Icon>
