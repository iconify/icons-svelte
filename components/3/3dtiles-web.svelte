<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhi5oybze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bhi5oybze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:3dtiles-web" {...props}></Icon>
