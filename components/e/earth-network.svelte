<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sezzy1b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="sezzy1b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-network" {...props}></Icon>
