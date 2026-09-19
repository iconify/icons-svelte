<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5z7n2dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ft5z7n2dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:paste-outline" {...props}></Icon>
