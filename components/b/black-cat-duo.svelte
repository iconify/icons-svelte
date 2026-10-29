<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lbnt75byn.css';
import '../../css/w/w27peibbj.css';
import '../../css/s/scgb-sjtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lbnt75byn"/><path class="w27peibbj wm-a"/><path class="scgb-sjtz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:black-cat-duo" {...props}></Icon>
