<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a34olsbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a34olsbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:draft2digital" {...props}></Icon>
