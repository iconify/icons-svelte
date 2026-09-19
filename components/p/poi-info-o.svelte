<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je4z95b1p.css';
import '../../css/d/dxj4yybcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="je4z95b1p"/><path class="dxj4yybcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-info-o" {...props}></Icon>
