<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvsna5bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="dvsna5bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:ethereum" {...props}></Icon>
