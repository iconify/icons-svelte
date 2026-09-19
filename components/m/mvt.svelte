<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2aclzb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="x2aclzb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:mvt" {...props}></Icon>
