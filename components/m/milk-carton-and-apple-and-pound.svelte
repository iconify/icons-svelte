<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-rn6bcfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m-rn6bcfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:milk-carton-and-apple-and-pound" {...props}></Icon>
