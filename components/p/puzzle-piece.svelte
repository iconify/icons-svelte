<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5u0dpbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5u0dpbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:puzzle-piece" {...props}></Icon>
