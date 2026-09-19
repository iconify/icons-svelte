<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gztstl2_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gztstl2_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rotate-counterclockwise-alt-filled" {...props}></Icon>
