<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ovwm4ub3k.css';
import '../../css/u/uw5p3bcjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ovwm4ub3k"/><path clip-rule="evenodd" class="uw5p3bcjt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-alert-solid" {...props}></Icon>
