<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-5jgsb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z-5jgsb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:glass-cheers" {...props}></Icon>
