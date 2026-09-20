<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8nap2xtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8nap2xtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-excel-box" {...props}></Icon>
