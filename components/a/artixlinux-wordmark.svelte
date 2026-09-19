<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbqrb3a2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sbqrb3a2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:artixlinux-wordmark" {...props}></Icon>
