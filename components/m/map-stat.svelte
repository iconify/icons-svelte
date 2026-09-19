<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n502x1bvx.css';
import '../../css/q/qcwre9owc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="n502x1bvx"/><path class="qcwre9owc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-stat" {...props}></Icon>
