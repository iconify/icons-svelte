<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbe06zb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbe06zb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:comments" {...props}></Icon>
