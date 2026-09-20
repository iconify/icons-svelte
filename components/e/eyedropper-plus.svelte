<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozs0v31rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozs0v31rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eyedropper-plus" {...props}></Icon>
