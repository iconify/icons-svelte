<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye5tomb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye5tomb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:menu-notification-filled" {...props}></Icon>
