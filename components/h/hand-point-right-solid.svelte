<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrrqhabty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lrrqhabty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-point-right-solid" {...props}></Icon>
