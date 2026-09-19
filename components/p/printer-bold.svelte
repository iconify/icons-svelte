<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3kb4cgpl.css';
import '../../css/q/q1oo2lbjw.css';
import '../../css/h/hi30kmb4w.css';
import '../../css/r/r67uvtzmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="r3kb4cgpl"><path class="q1oo2lbjw"/><path class="hi30kmb4w"/><path class="r67uvtzmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:printer-bold" {...props}></Icon>
