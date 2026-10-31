<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy9r3v0qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy9r3v0qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-gloss" {...props}></Icon>
