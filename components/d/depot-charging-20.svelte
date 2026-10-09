<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no8_0h65g.css';
import '../../css/e/eyio-_5vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="no8_0h65g"/><path class="eyio-_5vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:depot-charging-20" {...props}></Icon>
