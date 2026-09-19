<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evelimbep.css';
import '../../css/x/xyq_9lbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="evelimbep"/><path class="xyq_9lbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-smiley" {...props}></Icon>
