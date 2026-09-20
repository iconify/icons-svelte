<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7iw6bc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m7iw6bc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bowling-alley" {...props}></Icon>
