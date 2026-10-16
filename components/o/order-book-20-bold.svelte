<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4m5opfgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m4m5opfgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:order-book-20-bold" {...props}></Icon>
