<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvilx1q3c.css';
import '../../css/o/oaj3dytkx.css';
import '../../css/p/p4n8c8b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="oaj3dytkx"/><path class="p4n8c8b1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:big-x" {...props}></Icon>
