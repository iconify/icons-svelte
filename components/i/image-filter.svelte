<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjoe5boep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wjoe5boep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:image-filter" {...props}></Icon>
