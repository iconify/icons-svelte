<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4qrphzta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="u4qrphzta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:grid" {...props}></Icon>
