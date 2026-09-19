<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb-tadh8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jb-tadh8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-poi" {...props}></Icon>
