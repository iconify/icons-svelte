<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq0i1mbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zq0i1mbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:magnify-map" {...props}></Icon>
