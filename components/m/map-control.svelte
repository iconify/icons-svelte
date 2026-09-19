<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajnm6ob_j.css';
import '../../css/c/cscweibfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ajnm6ob_j"/><path class="cscweibfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-control" {...props}></Icon>
