<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-18jsbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="z-18jsbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-slash-o" {...props}></Icon>
