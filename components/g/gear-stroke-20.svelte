<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jow4vojth.css';
import '../../css/k/k3_q2gqev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jow4vojth"/><path class="k3_q2gqev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:gear-stroke-20" {...props}></Icon>
