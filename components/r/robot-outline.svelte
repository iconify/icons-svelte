<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afyoo0b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="afyoo0b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:robot-outline" {...props}></Icon>
