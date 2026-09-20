<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv1ourhyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dv1ourhyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ipvanish-dark" {...props}></Icon>
