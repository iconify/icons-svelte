<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw4rwyb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="nw4rwyb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:highlighter" {...props}></Icon>
