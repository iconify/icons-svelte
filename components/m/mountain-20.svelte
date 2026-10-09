<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoskafp8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hoskafp8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-20" {...props}></Icon>
