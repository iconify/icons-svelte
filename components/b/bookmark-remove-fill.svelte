<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtxhzw-ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtxhzw-ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-remove-fill" {...props}></Icon>
