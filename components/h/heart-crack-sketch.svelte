<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qz7xklilu.css';
import '../../css/v/vuuwxkj-f.css';
import '../../css/x/x50jb-e5t.css';
import '../../css/h/h5x3xzb0w.css';
import '../../css/o/o7y4z0d9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qz7xklilu"/><path class="vuuwxkj-f wm-k"/><path class="wm-a x50jb-e5t"/><path class="h5x3xzb0w wm-k"/><path class="o7y4z0d9x wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-crack-sketch" {...props}></Icon>
