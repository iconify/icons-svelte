<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl10r0bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nl10r0bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:height-map" {...props}></Icon>
