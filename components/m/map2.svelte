<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umbp655yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="umbp655yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:map2" {...props}></Icon>
