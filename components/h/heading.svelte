<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2-b6yigu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p2-b6yigu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:heading" {...props}></Icon>
