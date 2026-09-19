<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk0j2gbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xk0j2gbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:info-fill-12" {...props}></Icon>
