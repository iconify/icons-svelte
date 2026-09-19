<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttc7fgbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ttc7fgbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:compass-rose" {...props}></Icon>
