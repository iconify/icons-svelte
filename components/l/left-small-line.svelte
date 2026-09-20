<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp8tl5bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp8tl5bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:left-small-line" {...props}></Icon>
