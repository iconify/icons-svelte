<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_f70lduw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u_f70lduw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bullseye" {...props}></Icon>
