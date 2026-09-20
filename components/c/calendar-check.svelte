<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xck5rbc3z.css';
import '../../css/g/g70z56b6i.css';
import '../../css/w/wqj33hb5g.css';
import '../../css/z/zggadzblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="g70z56b6i"/><path class="wqj33hb5g"/><path class="zggadzblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:calendar-check" {...props}></Icon>
