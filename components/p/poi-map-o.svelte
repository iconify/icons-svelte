<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq6a8xb0a.css';
import '../../css/o/okbbhw_ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="tq6a8xb0a"/><path class="okbbhw_ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-map-o" {...props}></Icon>
