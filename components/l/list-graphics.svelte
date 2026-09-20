<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmnwi0bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bmnwi0bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:list-graphics" {...props}></Icon>
