<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9lkhrbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c9lkhrbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:pano-indicator" {...props}></Icon>
