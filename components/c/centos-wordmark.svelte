<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfv4ynbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gfv4ynbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:centos-wordmark" {...props}></Icon>
