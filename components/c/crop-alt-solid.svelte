<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzvb8wm7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mzvb8wm7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:crop-alt-solid" {...props}></Icon>
