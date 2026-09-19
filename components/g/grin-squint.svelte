<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y739aabdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="y739aabdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-squint" {...props}></Icon>
