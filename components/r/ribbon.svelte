<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe91o3b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fe91o3b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ribbon" {...props}></Icon>
