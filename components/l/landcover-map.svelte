<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec0legbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ec0legbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:landcover-map" {...props}></Icon>
