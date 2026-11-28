<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfad_mbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfad_mbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:atom" {...props}></Icon>
