<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn8e2rbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="xn8e2rbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:motorcycle" {...props}></Icon>
