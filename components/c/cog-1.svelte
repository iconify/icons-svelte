<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a088n9bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a088n9bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:cog-1" {...props}></Icon>
