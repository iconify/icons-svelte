<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_0g25s7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u_0g25s7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:earth" {...props}></Icon>
