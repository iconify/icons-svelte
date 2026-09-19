<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u66q5t6jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":432};
const content = `<path class="u66q5t6jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:notifications-none" {...props}></Icon>
