<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xo-byvivj.css';
import '../../css/a/a5qjus6jt.css';
import '../../css/q/qdkjvlb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xo-byvivj"/><rect class="a5qjus6jt"/><path class="qdkjvlb1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:keyboard" {...props}></Icon>
