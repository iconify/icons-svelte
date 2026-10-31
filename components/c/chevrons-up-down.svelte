<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aujswp2yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aujswp2yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:chevrons-up-down" {...props}></Icon>
