<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3p5udwiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3p5udwiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:globe-refresh" {...props}></Icon>
