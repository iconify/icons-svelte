<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh-axobrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="oh-axobrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-layout-border-top-border-cell-format-formatting-top" {...props}></Icon>
