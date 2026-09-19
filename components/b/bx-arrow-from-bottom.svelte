<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvxld2hkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvxld2hkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-arrow-from-bottom" {...props}></Icon>
