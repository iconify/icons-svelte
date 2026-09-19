<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0qkuvese.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="r0qkuvese"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:projection-screen" {...props}></Icon>
