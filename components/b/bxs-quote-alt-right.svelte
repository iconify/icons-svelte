<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwww3cbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwww3cbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-quote-alt-right" {...props}></Icon>
