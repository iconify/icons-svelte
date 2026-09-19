<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4723bcit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="i4723bcit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bike-outline" {...props}></Icon>
