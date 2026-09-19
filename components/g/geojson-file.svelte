<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks04u331z.css';
import '../../css/a/a-sqa4bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ks04u331z"/><path class="a-sqa4bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:geojson-file" {...props}></Icon>
