<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfjhs7b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sfjhs7b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:africa-and-madagascar" {...props}></Icon>
