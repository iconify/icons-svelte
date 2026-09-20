<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl33snbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rl33snbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:road" {...props}></Icon>
