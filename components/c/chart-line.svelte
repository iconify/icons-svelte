<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb3g6wplf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fb3g6wplf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:chart-line" {...props}></Icon>
