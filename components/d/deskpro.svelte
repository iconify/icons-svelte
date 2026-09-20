<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_c5a0bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l_c5a0bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:deskpro" {...props}></Icon>
