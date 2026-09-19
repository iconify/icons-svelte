<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhgjpo-5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lhgjpo-5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cloudflare-wordmark" {...props}></Icon>
