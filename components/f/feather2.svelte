<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pduisccio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pduisccio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:feather2" {...props}></Icon>
