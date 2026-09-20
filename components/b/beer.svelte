<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsg2jbb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fsg2jbb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:beer" {...props}></Icon>
