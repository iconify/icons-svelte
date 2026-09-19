<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3gx4zblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p3gx4zblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:keycap-bold" {...props}></Icon>
