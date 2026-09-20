<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opupg0b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="opupg0b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-add-2-remove-bold-cross-buttons-button-add-plus" {...props}></Icon>
