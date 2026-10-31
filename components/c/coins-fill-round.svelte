<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_be7nb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_be7nb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:coins-fill-round" {...props}></Icon>
