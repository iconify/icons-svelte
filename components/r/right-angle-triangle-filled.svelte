<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3xdq8b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3xdq8b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:right-angle-triangle-filled" {...props}></Icon>
