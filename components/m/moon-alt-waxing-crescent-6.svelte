<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs2jczbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="qs2jczbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waxing-crescent-6" {...props}></Icon>
