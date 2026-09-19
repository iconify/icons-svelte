<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1j1_gbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1j1_gbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-arrow-from-bottom" {...props}></Icon>
