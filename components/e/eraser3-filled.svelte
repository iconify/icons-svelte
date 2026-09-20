<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugd28mosf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugd28mosf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eraser3-filled" {...props}></Icon>
