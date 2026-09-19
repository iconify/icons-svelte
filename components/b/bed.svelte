<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yih36_51r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yih36_51r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bed" {...props}></Icon>
