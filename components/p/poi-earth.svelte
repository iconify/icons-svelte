<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4isnmu4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="s4isnmu4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-earth" {...props}></Icon>
