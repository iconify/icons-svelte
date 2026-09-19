<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff_0uo-vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ff_0uo-vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-horns-outline" {...props}></Icon>
