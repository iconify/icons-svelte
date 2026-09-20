<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz4gg-7av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz4gg-7av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pin-2-bold" {...props}></Icon>
