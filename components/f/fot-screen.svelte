<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3drjxgry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3drjxgry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:fot-screen" {...props}></Icon>
