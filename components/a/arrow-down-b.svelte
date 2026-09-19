<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_uy_9btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f_uy_9btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-down-b" {...props}></Icon>
