<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib4xsfe2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ib4xsfe2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:adjust" {...props}></Icon>
