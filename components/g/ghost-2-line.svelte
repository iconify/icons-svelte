<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryd3g7nyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryd3g7nyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ghost-2-line" {...props}></Icon>
