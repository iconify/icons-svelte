<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb3ggp-ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="sb3ggp-ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:facebook-f" {...props}></Icon>
