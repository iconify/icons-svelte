<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp7je4b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fp7je4b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-with-crack" {...props}></Icon>
