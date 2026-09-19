<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4-i4ybyx.css';
import '../../css/c/c98at3bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4-i4ybyx"/><path class="c98at3bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-check-square" {...props}></Icon>
