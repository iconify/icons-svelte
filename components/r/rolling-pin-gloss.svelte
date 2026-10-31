<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt8yg5lzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt8yg5lzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rolling-pin-gloss" {...props}></Icon>
