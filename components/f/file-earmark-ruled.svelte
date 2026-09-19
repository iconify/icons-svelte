<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2cpz77ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g2cpz77ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-ruled" {...props}></Icon>
