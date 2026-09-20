<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghjy1xb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghjy1xb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:obb" {...props}></Icon>
