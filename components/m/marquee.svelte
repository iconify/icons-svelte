<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axi0zrbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="axi0zrbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:marquee" {...props}></Icon>
