<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzcxy2o3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="uzcxy2o3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:measure-area" {...props}></Icon>
