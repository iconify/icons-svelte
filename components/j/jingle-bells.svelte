<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ll7svlg2u.css';
import '../../css/d/d-isrd9sw.css';
import '../../css/f/fm-m90lxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ll7svlg2u"/><path class="d-isrd9sw wm-a"/><path class="fm-m90lxt wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:jingle-bells" {...props}></Icon>
