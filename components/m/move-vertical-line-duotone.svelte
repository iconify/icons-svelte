<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jp1ilnbst.css';
import '../../css/x/x07ftrzei.css';
import '../../css/w/w4qe5y36z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jp1ilnbst"/><path class="x07ftrzei"/><path class="w4qe5y36z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-vertical-line-duotone" {...props}></Icon>
