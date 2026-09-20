<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut4blebfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut4blebfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home-trend-up-filled" {...props}></Icon>
