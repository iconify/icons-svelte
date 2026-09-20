<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycjak9csk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ycjak9csk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:add-to-cart-16" {...props}></Icon>
