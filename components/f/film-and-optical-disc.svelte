<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he1c9nb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="he1c9nb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:film-and-optical-disc" {...props}></Icon>
