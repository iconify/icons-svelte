<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmxrkys1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vmxrkys1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:browserstack-wordmark" {...props}></Icon>
