<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoj1vqbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoj1vqbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-coordinate-system-filled" {...props}></Icon>
