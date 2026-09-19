<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxdp1rbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wxdp1rbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cog" {...props}></Icon>
