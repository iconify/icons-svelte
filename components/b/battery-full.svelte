<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zopwkq5cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zopwkq5cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:battery-full" {...props}></Icon>
