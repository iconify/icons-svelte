<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odpp73b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="odpp73b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:marker" {...props}></Icon>
