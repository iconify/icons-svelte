<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pou3q3wuy.css';
import '../../css/v/vj_fb8bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pou3q3wuy"/><path class="vj_fb8bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-home-circle" {...props}></Icon>
