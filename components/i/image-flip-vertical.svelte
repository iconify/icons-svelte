<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf7od_ncm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gf7od_ncm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:image-flip-vertical" {...props}></Icon>
