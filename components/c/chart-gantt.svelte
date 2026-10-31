<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/b8s5p2bbo.css';
import '../../css/f/fanskmukn.css';
import '../../css/e/e2o-46l3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="b8s5p2bbo wm-shadow"/><path class="fanskmukn wm-shadow"/><path class="e2o-46l3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chart-gantt" {...props}></Icon>
