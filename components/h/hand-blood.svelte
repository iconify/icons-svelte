<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctris6r2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctris6r2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-blood" {...props}></Icon>
