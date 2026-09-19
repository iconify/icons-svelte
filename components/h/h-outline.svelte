<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmz29g4sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jmz29g4sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-outline" {...props}></Icon>
