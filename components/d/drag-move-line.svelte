<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbc_w3bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbc_w3bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drag-move-line" {...props}></Icon>
