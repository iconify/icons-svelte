<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utqr_sbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="utqr_sbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-half-stroke" {...props}></Icon>
