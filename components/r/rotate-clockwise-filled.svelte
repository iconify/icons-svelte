<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg4ykbbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mg4ykbbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rotate-clockwise-filled" {...props}></Icon>
