<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8kd97g9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f8kd97g9n st0"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:insert" {...props}></Icon>
