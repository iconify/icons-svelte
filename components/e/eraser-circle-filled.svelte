<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l693y2see.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l693y2see"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eraser-circle-filled" {...props}></Icon>
