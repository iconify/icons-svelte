<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2a3zwbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2a3zwbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-applause-filled" {...props}></Icon>
