<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4vtpdhjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4vtpdhjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:airplane-mode" {...props}></Icon>
