<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5b0hsbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x5b0hsbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-clockwise-20-solid" {...props}></Icon>
