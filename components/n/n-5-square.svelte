<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pso4n1bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="pso4n1bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:n-5-square" {...props}></Icon>
