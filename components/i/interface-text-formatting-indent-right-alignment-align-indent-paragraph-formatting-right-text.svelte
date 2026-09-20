<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqwid4b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sqwid4b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-indent-right-alignment-align-indent-paragraph-formatting-right-text" {...props}></Icon>
