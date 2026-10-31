<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3eh_mb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3eh_mb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flame-fill-round" {...props}></Icon>
