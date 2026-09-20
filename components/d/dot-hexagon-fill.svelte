<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip1i3acfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ip1i3acfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:dot-hexagon-fill" {...props}></Icon>
