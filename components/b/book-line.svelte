<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9_ipnbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9_ipnbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-line" {...props}></Icon>
