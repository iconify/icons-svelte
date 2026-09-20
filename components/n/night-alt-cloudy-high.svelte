<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_kpqtr2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="u_kpqtr2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-alt-cloudy-high" {...props}></Icon>
