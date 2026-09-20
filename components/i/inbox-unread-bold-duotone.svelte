<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n9vomcc2d.css';
import '../../css/n/n5fjpab4o.css';
import '../../css/q/q90e-8amo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n9vomcc2d"/><path class="n5fjpab4o"/><path class="q90e-8amo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-unread-bold-duotone" {...props}></Icon>
