<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc2ir_ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nc2ir_ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folder-closed-stroke-16" {...props}></Icon>
