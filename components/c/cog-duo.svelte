<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt9d2mb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vt9d2mb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cog-duo" {...props}></Icon>
