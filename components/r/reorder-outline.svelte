<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l2r4blint.css';
import '../../css/g/g6gtmxbue.css';
import '../../css/p/pxc43wbmd.css';
import '../../css/n/nyhs13d2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l2r4blint"/><path class="g6gtmxbue"/><path class="pxc43wbmd"/><path class="nyhs13d2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-outline" {...props}></Icon>
