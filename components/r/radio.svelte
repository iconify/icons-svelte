<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zq1q3021a.css';
import '../../css/s/s5a9wrp7u.css';
import '../../css/a/awed_9l6n.css';
import '../../css/g/gfovhfd2g.css';
import '../../css/i/iaz41ubnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zq1q3021a"/><path class="s5a9wrp7u"/><path class="awed_9l6n"/><path class="gfovhfd2g"/><path class="iaz41ubnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:radio" {...props}></Icon>
