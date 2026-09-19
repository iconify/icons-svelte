<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w603acbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="w603acbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-hydro" {...props}></Icon>
