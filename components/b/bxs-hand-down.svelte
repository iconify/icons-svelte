<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-r8gnast.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-r8gnast"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hand-down" {...props}></Icon>
