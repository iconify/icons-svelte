<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv1v87bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="dv1v87bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:frog" {...props}></Icon>
