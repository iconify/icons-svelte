<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-lohbbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="k-lohbbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-all-direction-move-button-arrows-direction" {...props}></Icon>
