<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lze9kx9yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lze9kx9yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rallly-dark" {...props}></Icon>
