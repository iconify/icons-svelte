<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggiu84btg.css';
import '../../css/p/pf2d4z5hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ggiu84btg"/><path class="pf2d4z5hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-play" {...props}></Icon>
