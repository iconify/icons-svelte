<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcr7hsbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="fcr7hsbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bucket" {...props}></Icon>
