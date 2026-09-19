<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw-_hobbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="kw-_hobbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mars-and-venus-burst" {...props}></Icon>
