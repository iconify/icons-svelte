<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehybqib_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ehybqib_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:place-of-worship-11" {...props}></Icon>
