<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6jf7qujf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j6jf7qujf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:instagram" {...props}></Icon>
