<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgf8wccyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgf8wccyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-pen" {...props}></Icon>
