<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzoxg7_fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mzoxg7_fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-indent-increase-alignment-align-indent-paragraph-increase-formatting-text" {...props}></Icon>
