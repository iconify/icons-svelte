<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/q/q92t2nk7r.css';
import '../../css/i/iolhn0crn.css';
import '../../css/j/jtcxpwb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="q92t2nk7r"/><path class="iolhn0crn"/><path class="jtcxpwb7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:airpods" {...props}></Icon>
