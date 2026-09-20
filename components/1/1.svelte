<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgne4ny2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mgne4ny2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:1" {...props}></Icon>
