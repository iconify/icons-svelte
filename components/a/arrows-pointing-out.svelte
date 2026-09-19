<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fguy6clur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fguy6clur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrows-pointing-out" {...props}></Icon>
