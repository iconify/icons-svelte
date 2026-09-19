<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrvehib-t.css';
import '../../css/x/xm21wv__h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rrvehib-t"/><path class="xm21wv__h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:esri-json-file" {...props}></Icon>
