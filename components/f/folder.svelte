<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2cn-0pih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="u2cn-0pih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:folder" {...props}></Icon>
