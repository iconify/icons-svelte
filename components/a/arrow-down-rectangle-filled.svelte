<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iim0fhzkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iim0fhzkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-down-rectangle-filled" {...props}></Icon>
