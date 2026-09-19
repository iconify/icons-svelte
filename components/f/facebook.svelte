<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tchbe2b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tchbe2b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:facebook" {...props}></Icon>
