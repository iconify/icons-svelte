<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxjr4wgbv.css';
import '../../css/z/z-gn40b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxjr4wgbv"/><path class="z-gn40b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:building-4-filled" {...props}></Icon>
