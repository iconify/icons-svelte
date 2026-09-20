<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp234nypf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tp234nypf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-design-tool-selection-wand-sselection-wand-object-work" {...props}></Icon>
