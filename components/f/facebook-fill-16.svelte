<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi8zxrbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pi8zxrbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:facebook-fill-16" {...props}></Icon>
