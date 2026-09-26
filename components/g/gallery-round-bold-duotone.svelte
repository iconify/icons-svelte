<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c0tsxrhtd.css';
import '../../css/d/d6gur6bsq.css';
import '../../css/y/y_8irlb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c0tsxrhtd"/><path clip-rule="evenodd" class="d6gur6bsq"/><path class="y_8irlb1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-round-bold-duotone" {...props}></Icon>
