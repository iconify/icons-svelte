<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrswrcl3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrswrcl3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:archive-check" {...props}></Icon>
