<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0_-0zbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0_-0zbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:edit-off-04" {...props}></Icon>
