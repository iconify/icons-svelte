<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0r65vbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0r65vbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bookmark-solid-expressive" {...props}></Icon>
