<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwdo5clsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uwdo5clsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bee-skep" {...props}></Icon>
