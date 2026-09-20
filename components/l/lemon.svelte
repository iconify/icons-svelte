<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3g4q6bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y3g4q6bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:lemon" {...props}></Icon>
