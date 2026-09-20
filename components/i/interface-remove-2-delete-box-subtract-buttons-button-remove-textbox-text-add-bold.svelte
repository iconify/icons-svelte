<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuik6ebaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<rect class="iuik6ebaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-remove-2-delete-box-subtract-buttons-button-remove-textbox-text-add-bold" {...props}></Icon>
