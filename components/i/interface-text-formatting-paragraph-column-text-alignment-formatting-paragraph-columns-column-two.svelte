<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1o_7ksyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u1o_7ksyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-paragraph-column-text-alignment-formatting-paragraph-columns-column-two" {...props}></Icon>
