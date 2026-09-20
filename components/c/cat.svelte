<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bc-x7obgt.css';
import '../../css/a/adfatdb-x.css';
import '../../css/a/adrmq1-1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bc-x7obgt"/><path class="adfatdb-x"/><path class="adrmq1-1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cat" {...props}></Icon>
