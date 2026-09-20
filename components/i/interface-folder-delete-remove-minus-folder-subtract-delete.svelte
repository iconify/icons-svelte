<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eonvu3b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="eonvu3b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-folder-delete-remove-minus-folder-subtract-delete" {...props}></Icon>
