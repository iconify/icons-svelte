<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0z5keb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y0z5keb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:compass-south-west" {...props}></Icon>
