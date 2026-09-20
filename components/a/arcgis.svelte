<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn68_t3-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn68_t3-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:arcgis" {...props}></Icon>
