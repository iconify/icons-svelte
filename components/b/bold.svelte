<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0_dr5q8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0_dr5q8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:bold" {...props}></Icon>
