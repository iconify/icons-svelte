<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4mytzbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r4mytzbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-pencil-change-edit-modify-pencil-write-writing" {...props}></Icon>
