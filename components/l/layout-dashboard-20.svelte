<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9xc3xfxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f9xc3xfxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-dashboard-20" {...props}></Icon>
