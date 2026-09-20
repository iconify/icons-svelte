<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck07mpvte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck07mpvte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:projector-line" {...props}></Icon>
