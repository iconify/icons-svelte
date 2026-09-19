<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtu_2e0sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtu_2e0sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-left-alt-filled" {...props}></Icon>
