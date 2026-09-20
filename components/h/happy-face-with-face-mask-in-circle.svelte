<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4jzllbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z4jzllbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:happy-face-with-face-mask-in-circle" {...props}></Icon>
