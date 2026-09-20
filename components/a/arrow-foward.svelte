<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5q0ggb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5q0ggb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-foward" {...props}></Icon>
