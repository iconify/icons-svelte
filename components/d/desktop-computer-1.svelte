<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1c5o8llx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1c5o8llx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:desktop-computer-1" {...props}></Icon>
