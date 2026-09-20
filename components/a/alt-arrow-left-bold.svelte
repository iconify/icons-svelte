<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhta4sb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhta4sb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-left-bold" {...props}></Icon>
