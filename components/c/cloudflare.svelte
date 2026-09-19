<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/few52z2af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="few52z2af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cloudflare" {...props}></Icon>
