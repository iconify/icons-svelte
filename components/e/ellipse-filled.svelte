<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8-_5gdxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8-_5gdxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ellipse-filled" {...props}></Icon>
