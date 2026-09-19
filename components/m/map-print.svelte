<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r85c85bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="r85c85bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-print" {...props}></Icon>
