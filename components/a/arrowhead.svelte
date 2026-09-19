<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jccy-06wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jccy-06wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arrowhead" {...props}></Icon>
