<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5o3i-b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="z5o3i-b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:meteor-wordmark" {...props}></Icon>
