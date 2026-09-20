<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-pxf5beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d-pxf5beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:communications-tower" {...props}></Icon>
