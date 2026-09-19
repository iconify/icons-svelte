<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk4kwybym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="xk4kwybym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:neg-2" {...props}></Icon>
