<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2k4tnisn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g2k4tnisn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-delete-1-remove-add-button-buttons-delete" {...props}></Icon>
