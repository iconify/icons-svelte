<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kde8uybpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="kde8uybpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:e-bold" {...props}></Icon>
