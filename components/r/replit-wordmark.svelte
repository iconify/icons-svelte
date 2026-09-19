<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puv6w158o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="puv6w158o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:replit-wordmark" {...props}></Icon>
