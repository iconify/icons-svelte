<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8l-7zvse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8l-7zvse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eraser-fill-round" {...props}></Icon>
