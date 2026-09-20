<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juppfpb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="juppfpb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:facebook-f" {...props}></Icon>
