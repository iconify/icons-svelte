<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfwrwlbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xfwrwlbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:cheveron-outline-down" {...props}></Icon>
