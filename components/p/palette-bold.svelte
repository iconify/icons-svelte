<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg00pobiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hg00pobiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:palette-bold" {...props}></Icon>
