<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e17p_vdgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e17p_vdgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-text-strike-through-text-strike-through-formatting-format" {...props}></Icon>
