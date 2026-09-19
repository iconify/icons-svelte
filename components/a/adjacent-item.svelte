<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m2iwz_b-c.css';
import '../../css/d/d-7w0ebsy.css';
import '../../css/w/wqtq763ef.css';
import '../../css/j/j9k9ahbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="m2iwz_b-c"/><path class="d-7w0ebsy"/><path class="wqtq763ef"/><path class="j9k9ahbqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:adjacent-item" {...props}></Icon>
