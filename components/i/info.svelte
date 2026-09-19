<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9jx4mbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":512};
const content = `<path class="z9jx4mbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:info" {...props}></Icon>
