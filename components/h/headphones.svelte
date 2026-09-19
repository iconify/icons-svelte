<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_29jxy7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_29jxy7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:headphones" {...props}></Icon>
