<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7mn_xgnv.css';
import '../../css/s/s7wv4pbid.css';
import '../../css/y/yjsg9j51b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="h7mn_xgnv"><path class="s7wv4pbid"/><path class="yjsg9j51b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:female-outline" {...props}></Icon>
