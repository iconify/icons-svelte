<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rsgvqsbiw.css';
import '../../css/n/no17qlb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":19};
const content = `<g class="ft5dv1b6b"><path class="rsgvqsbiw"/><path class="no17qlb2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mintlify" {...props}></Icon>
