<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z-50yghlk.css';
import '../../css/w/wnkqwte3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z-50yghlk"/><path clip-rule="evenodd" class="wnkqwte3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-face-mask-outline-24px" {...props}></Icon>
