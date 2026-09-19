<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g87_r8bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="g87_r8bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:border-all" {...props}></Icon>
