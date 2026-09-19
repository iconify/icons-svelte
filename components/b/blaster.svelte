<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzj6rydhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fzj6rydhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:blaster" {...props}></Icon>
