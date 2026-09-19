<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xspkb44qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xspkb44qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-arrow-up-right" {...props}></Icon>
