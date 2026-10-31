<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6x76mbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6x76mbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eraser-round" {...props}></Icon>
