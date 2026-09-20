<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r26g7nbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r26g7nbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:minimize-line" {...props}></Icon>
