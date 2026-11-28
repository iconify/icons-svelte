<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b2u-o9mvb.css';
import '../../css/t/tmlpzdv0s.css';
import '../../css/x/xgp9xq0-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b2u-o9mvb"/><path class="tmlpzdv0s"/><path class="xgp9xq0-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hard-drive" {...props}></Icon>
