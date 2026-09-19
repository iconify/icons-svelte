<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m319vub_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="m319vub_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:compare-map" {...props}></Icon>
