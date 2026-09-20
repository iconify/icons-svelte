<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9lap0bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9lap0bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iframe-edit-outline" {...props}></Icon>
