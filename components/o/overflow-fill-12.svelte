<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/njrtzgfnc.css';
import '../../css/s/slwp9yb5h.css';
import '../../css/k/klebjebfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><circle class="njrtzgfnc"/><circle class="slwp9yb5h"/><circle class="klebjebfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:overflow-fill-12" {...props}></Icon>
