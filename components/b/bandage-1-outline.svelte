<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2bwcfkbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="u2bwcfkbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bandage-1-outline" {...props}></Icon>
