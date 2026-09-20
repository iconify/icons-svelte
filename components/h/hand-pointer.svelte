<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kddf7p6ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kddf7p6ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-pointer" {...props}></Icon>
