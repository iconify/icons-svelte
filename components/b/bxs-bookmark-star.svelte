<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ch7qbai.css';
import '../../css/b/bjm4ztbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ch7qbai"/><path class="bjm4ztbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bookmark-star" {...props}></Icon>
