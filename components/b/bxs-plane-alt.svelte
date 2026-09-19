<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfr71u25j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfr71u25j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-plane-alt" {...props}></Icon>
