<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6gzcks7d.css';
import '../../css/f/faefp84ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g6gzcks7d"/><path class="faefp84ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-earth" {...props}></Icon>
