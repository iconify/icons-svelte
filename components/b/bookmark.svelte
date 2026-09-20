<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7rviynjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x7rviynjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:bookmark" {...props}></Icon>
