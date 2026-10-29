<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/az496hjvu.css';
import '../../css/z/zi6tnccid.css';
import '../../css/v/vzibu2b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="az496hjvu"/><path class="zi6tnccid"/><path class="vzibu2b_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-pull-request-sketch" {...props}></Icon>
