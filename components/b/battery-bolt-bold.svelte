<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9y4ge1vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a9y4ge1vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-bolt-bold" {...props}></Icon>
