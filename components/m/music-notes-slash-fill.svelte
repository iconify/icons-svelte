<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8x6d_bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x8x6d_bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:music-notes-slash-fill" {...props}></Icon>
