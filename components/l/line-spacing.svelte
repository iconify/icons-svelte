<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe3j86vbb.css';
import '../../css/i/i8b66go_s.css';
import '../../css/v/vrmdo4bib.css';
import '../../css/i/i771m-bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe3j86vbb"/><path class="i8b66go_s"/><path class="vrmdo4bib"/><path class="i771m-bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:line-spacing" {...props}></Icon>
