<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-s6l5uoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-s6l5uoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-ai-fill" {...props}></Icon>
