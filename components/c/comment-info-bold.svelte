<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx2qfgb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zx2qfgb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-info-bold" {...props}></Icon>
