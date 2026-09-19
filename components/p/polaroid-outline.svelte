<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8ds3ac-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l8ds3ac-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:polaroid-outline" {...props}></Icon>
