<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu2nr00zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu2nr00zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:palette-1-filled" {...props}></Icon>
