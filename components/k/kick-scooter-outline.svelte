<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyvjlmb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fyvjlmb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:kick-scooter-outline" {...props}></Icon>
