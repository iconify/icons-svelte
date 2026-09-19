<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx81x8bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yx81x8bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mug-saucer" {...props}></Icon>
