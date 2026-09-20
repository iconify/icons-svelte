<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk4vp-xsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rk4vp-xsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-hr-dark" {...props}></Icon>
