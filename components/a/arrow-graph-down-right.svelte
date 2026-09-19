<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1pi5rbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m1pi5rbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-graph-down-right" {...props}></Icon>
