<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2hxwibdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p2hxwibdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mouse-pointer-outline" {...props}></Icon>
