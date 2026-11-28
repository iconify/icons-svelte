<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl1w0n5jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl1w0n5jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mic-play" {...props}></Icon>
