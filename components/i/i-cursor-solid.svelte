<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjcww6b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pjcww6b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:i-cursor-solid" {...props}></Icon>
