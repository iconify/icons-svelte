<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6yd1sbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="s6yd1sbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:address-book-o" {...props}></Icon>
