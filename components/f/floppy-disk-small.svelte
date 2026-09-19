<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk1f5g_bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vk1f5g_bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:floppy-disk-small" {...props}></Icon>
