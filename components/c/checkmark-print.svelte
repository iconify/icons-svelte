<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kldbyvy5v.css';
import '../../css/k/kaj75h1kd.css';
import '../../css/u/ux63s-ozf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kldbyvy5v"/><path class="kaj75h1kd"/><path class="ux63s-ozf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:checkmark-print" {...props}></Icon>
