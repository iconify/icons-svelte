<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/u/ubczdxbzu.css';
import '../../css/v/v5zmisb0l.css';
import '../../css/k/k73vt3bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="ubczdxbzu"/><path class="v5zmisb0l"/><path class="k73vt3bvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:box-open" {...props}></Icon>
