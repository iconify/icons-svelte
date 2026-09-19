<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uslc8omei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uslc8omei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:col-resize-filled" {...props}></Icon>
