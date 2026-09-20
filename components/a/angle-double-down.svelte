<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k46itubig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k46itubig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:angle-double-down" {...props}></Icon>
