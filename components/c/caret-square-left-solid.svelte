<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eugv6vbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eugv6vbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:caret-square-left-solid" {...props}></Icon>
