<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z12x-2b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z12x-2b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eraser-fill" {...props}></Icon>
