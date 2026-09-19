<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm0e28bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm0e28bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-sun" {...props}></Icon>
