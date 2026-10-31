<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/by_r6bbiz.css';
import '../../css/y/y_57knbko.css';
import '../../css/t/tad6awcii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="by_r6bbiz"/><path class="y_57knbko"/><path class="tad6awcii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:archive-arrow-down-duotone" {...props}></Icon>
