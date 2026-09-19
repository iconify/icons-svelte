<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqb2u5bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jqb2u5bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:clipboard-outline" {...props}></Icon>
