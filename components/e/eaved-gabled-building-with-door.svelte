<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgw24u_jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zgw24u_jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-gabled-building-with-door" {...props}></Icon>
