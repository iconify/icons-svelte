<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt-fu6bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt-fu6bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:collapse-horizontal-fill" {...props}></Icon>
