<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co_pena6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co_pena6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-color-fill" {...props}></Icon>
