<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnz5lbemc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hnz5lbemc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-select-frame-cursor-frame-select" {...props}></Icon>
