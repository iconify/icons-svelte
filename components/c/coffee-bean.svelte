<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xck5rbc3z.css';
import '../../css/k/k1tjfvb9o.css';
import '../../css/k/km7l-rbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="k1tjfvb9o"/><path class="km7l-rbnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:coffee-bean" {...props}></Icon>
