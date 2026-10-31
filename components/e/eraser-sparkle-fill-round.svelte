<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puznxsb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puznxsb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eraser-sparkle-fill-round" {...props}></Icon>
