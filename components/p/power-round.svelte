<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/calhe9bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="calhe9bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:power-round" {...props}></Icon>
