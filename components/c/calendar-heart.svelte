<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xck5rbc3z.css';
import '../../css/o/ox-f2-brs.css';
import '../../css/a/a4lf8gunw.css';
import '../../css/z/zggadzblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="ox-f2-brs"/><path class="a4lf8gunw"/><path class="zggadzblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:calendar-heart" {...props}></Icon>
