<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byem0y19c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="byem0y19c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hospital-h" {...props}></Icon>
