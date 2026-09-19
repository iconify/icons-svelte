<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a89ywegkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="a89ywegkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:rectangle-pt" {...props}></Icon>
