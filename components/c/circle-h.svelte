<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1h353i9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1h353i9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-h" {...props}></Icon>
