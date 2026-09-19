<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebt0b4bjw.css';
import '../../css/j/jpgdedcax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ebt0b4bjw"/><path class="jpgdedcax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-options" {...props}></Icon>
