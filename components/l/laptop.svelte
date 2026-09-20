<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zogt6cb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zogt6cb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:laptop" {...props}></Icon>
