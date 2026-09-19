<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkk-mftzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkk-mftzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:eraser-auto" {...props}></Icon>
