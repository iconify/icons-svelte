<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfy499bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfy499bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:highlighter-round" {...props}></Icon>
