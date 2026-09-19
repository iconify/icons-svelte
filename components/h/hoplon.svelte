<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1-g0ub6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1-g0ub6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:hoplon" {...props}></Icon>
