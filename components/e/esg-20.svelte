<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkihj-w6g.css';
import '../../css/y/yhip1xbph.css';
import '../../css/y/yau-9gbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkihj-w6g"/><path class="yhip1xbph"/><path class="yau-9gbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:esg-20" {...props}></Icon>
