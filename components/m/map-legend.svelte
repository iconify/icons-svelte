<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akbunfx0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="akbunfx0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-legend" {...props}></Icon>
