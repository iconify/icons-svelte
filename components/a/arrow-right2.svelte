<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkdp20hab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xkdp20hab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-right2" {...props}></Icon>
