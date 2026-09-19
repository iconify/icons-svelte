<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms5-zbb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ms5-zbb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pennant-1-outline" {...props}></Icon>
