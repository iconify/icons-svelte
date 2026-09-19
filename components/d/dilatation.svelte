<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_cu6h09n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g_cu6h09n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:dilatation" {...props}></Icon>
