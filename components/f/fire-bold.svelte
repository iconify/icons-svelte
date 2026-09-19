<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbx1qqt1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fbx1qqt1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fire-bold" {...props}></Icon>
