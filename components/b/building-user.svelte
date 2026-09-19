<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykf6ek8cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ykf6ek8cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:building-user" {...props}></Icon>
