<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xantwab2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="xantwab2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-up-to-line" {...props}></Icon>
