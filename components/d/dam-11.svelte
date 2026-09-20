<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv8k65bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="uv8k65bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:dam-11" {...props}></Icon>
