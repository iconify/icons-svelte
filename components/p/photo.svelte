<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy9jgkulp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jy9jgkulp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:photo" {...props}></Icon>
