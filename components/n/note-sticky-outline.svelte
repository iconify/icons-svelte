<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6qqgkbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="t6qqgkbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-sticky-outline" {...props}></Icon>
