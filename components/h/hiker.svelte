<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_sa4jb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="e_sa4jb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:hiker" {...props}></Icon>
