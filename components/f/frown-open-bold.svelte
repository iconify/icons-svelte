<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqipt_dmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jqipt_dmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:frown-open-bold" {...props}></Icon>
