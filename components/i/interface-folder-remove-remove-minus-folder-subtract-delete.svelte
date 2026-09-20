<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjoof61_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pjoof61_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-folder-remove-remove-minus-folder-subtract-delete" {...props}></Icon>
