<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z8rknehdi.css';
import '../../css/z/zv1ng1bfo.css';
import '../../css/w/wabha5b6m.css';
import '../../css/i/iyduq7-od.css';
import '../../css/x/x2f5ebbeb.css';
import '../../css/l/lhyb3bbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z8rknehdi"/><path class="zv1ng1bfo"/><path class="wabha5b6m"/><path class="iyduq7-od wm-a"/><path class="wm-a x2f5ebbeb"/><path class="lhyb3bbbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:grape-duo" {...props}></Icon>
