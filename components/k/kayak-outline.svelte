<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0s98rd3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z0s98rd3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:kayak-outline" {...props}></Icon>
